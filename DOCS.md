Ten en cuenta cómo con onClick={() => alert('click')}, estamos pasando una función como valor del prop onClick. React solo llamará a esta función después de un click. Olvidar () => y escribir onClick={alert('click')} es un error común, y ejecutaría la alerta cada vez que el componente se re-renderice.


En las clases de JavaScript, necesitas siempre llamar super cuando defines el constructor de una subclase. Todas las clases de componentes de React que tienen un constructor deben empezar con una llamada a super(props).
