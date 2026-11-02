# Guia de contribucion

Gracias por querer mejorar Tienda TECSUP. Sigue estas reglas para que tu aporte se revise rapido.

## Como reportar un error

1. Entra a la pestana **Issues** del repositorio y haz clic en **New issue**.
2. Escribe un titulo que diga el problema, por ejemplo: `El total del carrito no multiplica el precio por la cantidad`.
3. En la descripcion responde las cuatro preguntas:
   - **Que esperaba:** lo que deberia pasar.
   - **Que ocurre:** lo que pasa en realidad.
   - **Donde:** archivo y linea.
   - **Como reproducirlo:** los pasos para ver el error.

## Como proponer una mejora

1. Haz un fork del repositorio.
2. Crea una rama con un nombre que diga que arregla: `git checkout -b fix-nombre-del-cambio`
3. Haz el cambio y pruebalo en el navegador.
4. Guarda el cambio: `git commit -m "Describe tu cambio (#numero-del-issue)"`
5. Sube la rama: `git push origin fix-nombre-del-cambio`
6. Abre un Pull Request y escribe `Cierra el issue #numero` en la descripcion.

## Checklist antes de enviar un Pull Request

- [ ] Cree el cambio en una rama nueva, no en main
- [ ] Probe el cambio en el navegador
- [ ] Revise el cambio con `git diff`
- [ ] El Pull Request modifica un solo archivo
- [ ] La descripcion menciona el numero del Issue