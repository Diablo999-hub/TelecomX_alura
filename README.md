# TelecomX_alura

Análisis de datos de clientes del sector telecomunicaciones en LATAM

## Descripción

Este proyecto realiza un análisis de datos de clientes de una empresa de telecomunicaciones, enfocado en la predicción y entendimiento del fenómeno de **Churn** (deserción de clientes). Utiliza Python y Jupyter Notebook para la extracción, transformación y exploración de los datos.

## Contenido

El análisis sigue estos pasos principales:

1. **Extracción de datos:**  
   Se obtienen los datos en formato JSON desde un recurso en línea y se cargan en un DataFrame de pandas.

2. **Transformación:**  
   Los datos anidados se normalizan y se genera un DataFrame plano donde cada columna representa una característica relevante del cliente, sus servicios y sus pagos.

3. **Exploración y diccionario de datos:**  
   Se exploran las primeras filas y se documenta el significado de cada columna, incluyendo variables demográficas, de servicio contratado, facturación y si el cliente abandonó la empresa (Churn).

## Diccionario de datos

- **customerID:** Identificador único del cliente
- **Churn:** Si el cliente desertó o no
- **customer.gender:** Género
- **customer.SeniorCitizen:** Si el cliente es mayor de 65 años
- **customer.Partner:** Si tiene pareja
- **customer.Dependents:** Si tiene dependientes
- **customer.tenure:** Meses que lleva como cliente
- **phone.PhoneService:** Tiene servicio telefónico
- **phone.MultipleLines:** Tiene múltiples líneas
- **internet.InternetService:** Tipo de internet
- **internet.OnlineSecurity:** Servicio de seguridad en línea
- **internet.OnlineBackup:** Servicio de respaldo en línea
- **internet.DeviceProtection:** Protección de dispositivo
- **internet.TechSupport:** Soporte técnico
- **internet.StreamingTV:** Streaming de TV
- **internet.StreamingMovies:** Streaming de películas
- **account.Contract:** Tipo de contrato
- **account.PaperlessBilling:** Facturación electrónica
- **account.PaymentMethod:** Método de pago
- **account.Charges.Monthly:** Cargo mensual total
- **account.Charges.Total:** Cargo total acumulado

## Requisitos

- Python 3.x
- Jupyter Notebook
- Librerías:  
  - pandas  
  - numpy  
  - requests  

Puedes instalar las librerías necesarias con:

```bash
pip install pandas numpy requests
```

## Ejecución

1. Clona este repositorio:
   ```bash
   git clone https://github.com/Diablo999-hub/TelecomX_alura.git
   ```
2. Abre el archivo `TelecomX_LATAM.ipynb` en Jupyter Notebook o Google Colab.
3. Ejecuta las celdas para reproducir el análisis.
