### About
Fields for [vue-form-generator-gt4w](https://github.com/gt4w-consultoria/vue-form-generator-gt4w) module with [Element css framework](http://element.eleme.io). 

### Usage

```$xslt
yarn add vue-form-generator-element-gt4w
```

Add following code in main.js:
```$xslt
import VueFormGeneratorElement from 'vue-form-generator-element-gt4w'
Vue.use(VueFormGeneratorElement)
```

Import and register the component (vue-form-generator) in the template:
```$xslt
import { component as VueFormGenerator } from 'vue-form-generator'
export default {
...
  components: { VueFormGenerator },
...
}
```

Use in the template:
```$xslt
  vue-form-generator(:schema="schema", :model="model", :options="formOptions")
```

See usage [example](https://github.com/egorzot/vue-form-generator-element-example).

Fields list:

* [fieldElementInput](https://github.com/egorzot/vue-form-generator-element/blob/master/src/fields/fieldElementInput.vue)
* [fieldElementSelect](https://github.com/egorzot/vue-form-generator-element/blob/master/src/fields/fieldElementSelect.vue)
* [fieldElementRadio](https://github.com/egorzot/vue-form-generator-element/blob/master/src/fields/fieldElementRadio.vue)
* [fieldElementCheckbox](https://github.com/egorzot/vue-form-generator-element/blob/master/src/fields/fieldElementCheckbox.vue)
* [fieldElementDatePicker](https://github.com/egorzot/vue-form-generator-element/blob/master/src/fields/fieldElementDatePicker.vue)
* [fieldElementSwitch](https://github.com/egorzot/vue-form-generator-element/blob/master/src/fields/fieldElementSwitch.vue)
* [fieldElementTextArea](https://github.com/egorzot/vue-form-generator-element/blob/master/src/fields/fieldElementTextArea.vue)
* [fieldElementUpload](https://github.com/egorzot/vue-form-generator-element/blob/master/src/fields/fieldElementUpload.vue)
* [fieldElementColorPicker](https://github.com/egorzot/vue-form-generator-element/blob/master/src/fields/fieldElementColorPicker.vue)
* [fieldElementSlider](https://github.com/egorzot/vue-form-generator-element/blob/master/src/fields/fieldElementSlider.vue)

![Screenshot](https://egor.work/blog/pictures/screen.png)

### Contributing
PR's are welcome!
