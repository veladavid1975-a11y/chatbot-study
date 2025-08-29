# Chatbot Study - Semana 1 Día X

## Flujo actual en Landbot

Start  
   ↓  
Ask name → guarda en field: name  
   ↓  
Mensaje: "Encantado, @name. ¿Qué necesitas hoy?"  
   ↓  
Botones → guarda en field: menu_choice  
   ├── Ver productos  
   │      ↓  
   │   Mensaje: "Tenemos camisetas y gorras 😎"  
   │      ↓  
   │   Botones → guarda en field: menu_productos  
   │         ├── Ver precios → Mensaje con precios  
   │         └── Hacer una pregunta → Ask a question (texto libre)  
   │  
   └── Soporte  
          ↓  
       Mensaje: "Vale, @name. ¿Prefieres hablar con un agente o revisar las FAQs?"  
          ↓  
       Botones → guarda en field: menu_soporte  
              ├── Hablar con agente → Mensaje: "Te paso con un agente 👩‍💻"  
              └── Revisar FAQs → Mensaje con 2–3 FAQs  

## Metáfora personal
Para mí, **Git** es como las canciones que compongo, y **GitHub** es el álbum donde las publico.
## Mis próximos pasos
- Aprender a hacer commits desde mi computadora (no solo desde la web).
- Entender ramas (branches) para trabajar en paralelo.
- Este es mi primer cambio desde mi computadora 🚀
