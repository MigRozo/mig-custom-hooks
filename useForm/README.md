# useForm Hook
***

Ejemplo de uso:
```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };

    const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```

`useForm()` // Recibe un valor por defecto (`object`) para el formulario.
