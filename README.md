# MitAppInventor - Calculadora App

Proyecto de MIT App Inventor: una **calculadora interactiva** con bloques de programacion incluidos.

## Descripcion

Esta aplicacion es una calculadora basica creada con MIT App Inventor que permite realizar las 4 operaciones aritmeticas fundamentales. Incluye validacion de entrada y un historial de operaciones.

## Caracteristicas

- **Suma** - Suma dos numeros
- **Resta** - Resta dos numeros
- **Multiplicacion** - Multiplica dos numeros
- **Division** - Divide dos numeros (con proteccion contra division por cero)
- **Historial** - Muestra las operaciones realizadas
- **Limpiar** - Reinicia todos los campos

## Componentes de la interfaz (Screen1.scm)

| Componente | Tipo | Funcion |
|---|---|---|
| LabelTitulo | Label | Titulo de la app |
| LabelResultado | Label | Muestra el resultado |
| TextBoxNumero1 | TextBox | Entrada del primer numero |
| TextBoxNumero2 | TextBox | Entrada del segundo numero |
| LabelOperador | Label | Muestra el operador actual |
| ButtonSumar | Button | Ejecuta la suma |
| ButtonRestar | Button | Ejecuta la resta |
| ButtonMultiplicar | Button | Ejecuta la multiplicacion |
| ButtonDividir | Button | Ejecuta la division |
| ButtonLimpiar | Button | Limpia todos los campos |
| LabelHistorialContenido | Label | Muestra historial de operaciones |
| Notifier1 | Notifier | Alertas de validacion |

## Bloques incluidos (Screen1.bky)

La logica de la aplicacion incluye **5 bloques de eventos**:

1. **ButtonSumar.Click** - Valida entradas, suma, muestra resultado y agrega al historial
2. **ButtonRestar.Click** - Valida entradas, resta, muestra resultado y agrega al historial
3. **ButtonMultiplicar.Click** - Valida entradas, multiplica, muestra resultado y agrega al historial
4. **ButtonDividir.Click** - Valida entradas, verifica division por cero, divide, muestra resultado y agrega al historial
5. **ButtonLimpiar.Click** - Limpia TextBoxes, resultado, operador e historial

## Como importar en MIT App Inventor

1. Ve a [MIT App Inventor](https://ai2.appinventor.mit.edu/)
2. Haz clic en **Projects** > **Import project (.aia) from my computer**
3. Selecciona el archivo `CalculadoraApp.aia`
4. El proyecto se abrira con todos los componentes y bloques listos

## Estructura del proyecto

```
MitAppInventor/
├── CalculadoraApp.aia                              # Archivo importable en MIT App Inventor
├── youngandroidproject/
│   └── project.properties                          # Configuracion del proyecto
├── src/appinventor/ai_usuario/CalculadoraApp/
│   ├── Screen1.scm                                 # Definicion de componentes (interfaz)
│   └── Screen1.bky                                 # Definicion de bloques (logica)
└── README.md
```