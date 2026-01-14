# Tarea Dev Junior - Ruuf

## 🚀 Ejecución

### Opción 1: Solución en TypeScript sin display
```bash
npm install
npm start
```

### Opción 1: Solución en TypeScript con display
```bash
npm install express
npx ts-node main_w_display.ts
```
---

## 📝 Solución

Link del video explicando: https://youtu.be/68g3rhjt_ww

---

## 💰 Bonus (Opcional)

### Bonus Implementado

Implemente el bonus 1, un techo triangular, asumiendo que la base sería roof_width y la altura roof_height, y ademas que roof_width seria impar y que roof_height seria lo suficientemente grande como para no truncar el triangulo.

### Explicación del Bonus

Hubo dos alteraciones que se realizaron para resolver el bonus:
- Se agregó un booleano para decidir qué tipo de techo se requiere.
- Se agregó una sección que modifica las grillas de techo para rellenar los espacios no válidos con -1 y los que si son validos con 0, formando un triangulo isósceles cuyo vertice superior esta en el centro de la primera fila.

Una vez hecho esto, la logica es la misma que en el caso rectangular.

---

## 🤔 Supuestos y Decisiones

Hubo dos supuestos que se usaron al resolver el ejercicio:
- Los paneles solo pueden ir de manera horizontal o vertical, pues el agregar rotaciones adicionales aumenta la dificultad de una manera muy alta para el tiempo dado.
- Llenar el espacio con todos los paneles posibles en una dirección y luego en la otra resultará en la máxima cantidad de paneles.
