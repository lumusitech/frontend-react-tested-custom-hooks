# useForm Hook

### Ejemplo de uso:

```js
// initialForm recibe un estado inicial del formulario.
const initialForm = {
  name: '',
  email: '',
  age: 0,
};
const [formValues, handleInputChange, reset] = useForm(initialForm);
```
