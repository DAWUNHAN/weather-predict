# Weather Prediction in Australia
## π λ°ν μμ
[![νΈμ£Όλ μ¨μμΈ‘](https://img.youtube.com/vi/rIwDuQyhjqo/0.jpg)](https://youtu.be/rIwDuQyhjqo)

## π Data Collection
- νΈμ£Ό λ μ¨ λ°μ΄ν° (145460, 23)
- [λ°μ΄ν° μΆμ²: Kaggle](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)
- Columns
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/dataset.png?raw=true)
  <!-- - 'Date' : λ μ§,
  - 'Location' : μ₯μ,
  - 'MinTemp' : μ΅μ  μ¨λ (μ­μ¨),
  - 'MaxTemp' : μ΅κ³  μ¨λ (μ­μ¨),
  - 'Rainfall': κ°μλ (mm),
  - 'Evaporation' : μ¦λ°λ (mm),
  - 'Sunshine' : μΌμ‘° μκ° (hour),
  - 'WindGustDir' : κ°μ₯ κ°ν λ°λ λ°©ν₯,
  - 'WindGustSpeed' : κ°μ₯ κ°ν λ°λ μλ (km/h),
  - 'WindDir9am' : μ€μ  9μ λ°λ λ°©ν₯,
  - 'WindDir3pm' : μ€ν 3μ λ°λ λ°©ν₯,
  - 'WindSpeed9am': μ€μ  9μ λ°λ μλ (km/h),
  - 'WindSpeed3pm': μ€ν 3μ λ°λ μλ (km/h),
  - 'Humidity9am' : μ€μ  9μ μ΅λ (%),
  - 'Humidity3pm' : μ€ν 3μ μ΅λ (%),
  - 'Pressure9am' : μ€μ  9μμ νκ·  ν΄μλ©΄μΌλ‘ κ°μλ λκΈ°μ(hpa),
  - 'Pressure3pm' : μ€ν 3μμ νκ·  ν΄μλ©΄μΌλ‘ κ°μλ λκΈ°μ(hpa),
  - 'Cloud9am' : μ€μ  9μ κ΅¬λ¦λ (Many),
  - 'Cloud3pm' : μ€ν 3μ κ΅¬λ¦λ (Many),
  - 'Temp9am' : μ€μ  9μ μ¨λ (μ­μ¨),
  - 'Temp3pm' : μ€ν 3μ μ¨λ (μ­μ¨),
  - 'RainToday' : μ€λ κ°μ° μ¬λΆ (Boolean),
  - 'RainTomorrow' : λ΄μΌ κ°μ° μ¬λΆ (Boolean) -->
- νκ² : RainTomorrow (λ΄μΌ λΉκ° μ€λμ§ μ¬λΆ)

## π Data Preprocessing
- κ²°μΈ‘μΉ μ κ±°
  - 50,000 μ΄μμ κ²°μΈ‘μΉ κ°λ μ»¬λΌ μ κ±° : ['Evaporation', 'Sunshine', 'Cloud9am', 'Cloud3pm']
  - νκ²μ κ²°μΈ‘μΉ μλ row μ­μ 
- μ»¬λΌ μμ±
  - νκ·  μ΅λ, νκ·  κΈ°μ¨ μ»¬λΌ μμ±
  - μΈλ¨Έ νμμ κΈ°μ€μΌλ‘ μ¬λ¦κ³Ό non-μ¬λ¦ κ³μ  κ΅¬λΆ

## π μ¬μ©ν λ¨Έμ λ¬λ λͺ¨λΈ
- Random Forest
- XGBoost Classifier
- LightGBM Classifier

## π λ°ν μλ£
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/01.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/02.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/03.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/04.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/05.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/06.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/07.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/08.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/09.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/10.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/11.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/12.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/13.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/14.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/15.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/16.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/17.jpg?raw=true)
![](https://github.com/DAWUNHAN/Weather-Predict/blob/master/img/18.jpg?raw=true)
