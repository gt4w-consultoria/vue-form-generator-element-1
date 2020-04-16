### Sobre
Fields para [vue-form-generator-gt4w](https://github.com/gt4w-consultoria/vue-form-generator-gt4w) módulo com suporte para o [Element css framework](http://element.eleme.io).

### Como usar

Adicione a biblioteca:
```$xslt
yarn add vue-form-generator-element-gt4w
```

Adicione a biblioteca no `main.js`:
```$xslt
import VueFormGeneratorElement from 'vue-form-generator-element-gt4w'
Vue.use(VueFormGeneratorElement)
```

Importe e registre o componente (vue-form-generator) no template:
```$xslt
import { component as VueFormGenerator } from 'vue-form-generator'
export default {
...
  components: { VueFormGenerator },
...
}
```

Use no template:
```$xslt
  el-form
    vue-form-generator(:schema="schema", :model="model", :options="formOptions")
```

Todas propriedades e ajustes possíveis podem ser encontrados [aqui](https://github.com/egorzot/vue-form-generator-element-example) e [aqui](https://vue-generators.gitbook.io/vue-generators/).

### Props dessa biblioteca

Foram adicionadas novas props que podem ser passadas no JSON do `schema`, que dão suporte ao `grid` e `gutter`, basta passar dentro de cada field, exemplo:

```json
fields: [
  ...
  {
    ...
    column: 12,
    gutter: '40',
    ...
  }
]
```
O mesmo serve para o `groups`.

*Lembrando que as `rows` tem um total de `24` colunas, então se a soma de uma lnha passar de `24`, automaticamente o próximo field irá para a linha debaixo.*

Veja exemplo (biblioteca original) [exemplo](https://github.com/egorzot/vue-form-generator-element-example).

Lista de fields:

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
