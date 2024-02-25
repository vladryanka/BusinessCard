Выполните задание от Vibelab:
Создайте логирование используя приложение из предыдущего урока для каждого метода жизненного цикла activity, проверьте, что методы вызываются в нужной последовательности, просмотрите логи. Включите режим поворота экрана, осуществите поворот экрана, просмотрите логи. Сверните приложение, просмотрите логи. Напишите в методе onCreate() вызов метода finish(), просмотрите логи. Напишите логи по каждому пункту задания в файл Readme, обоснуйте результат.

логи приложения при открытии и закрытии приложения:
2024-02-25 11:44:30.846 20628-20628/com.smorzhok.businesscard D/MainActivity: OnCreate Method
2024-02-25 11:44:30.885 20628-20628/com.smorzhok.businesscard D/MainActivity: onStart Method
2024-02-25 11:44:30.887 20628-20628/com.smorzhok.businesscard D/MainActivity: onResume Method
2024-02-25 11:45:02.545 20628-20628/com.smorzhok.businesscard D/MainActivity: onPause Method
2024-02-25 11:45:02.585 20628-20628/com.smorzhok.businesscard D/MainActivity: onStop Method
2024-02-25 11:45:02.625 20628-20628/com.smorzhok.businesscard D/MainActivity: onDestroy Method


логи приложения при "Включите режим поворота экрана, осуществите поворот экрана, просмотрите логи."
2024-02-25 11:47:25.165 21045-21045/com.smorzhok.businesscard D/MainActivity: OnCreate Method
2024-02-25 11:47:25.198 21045-21045/com.smorzhok.businesscard D/MainActivity: onStart Method
2024-02-25 11:47:25.200 21045-21045/com.smorzhok.businesscard D/MainActivity: onResume Method
2024-02-25 11:47:32.090 21045-21045/com.smorzhok.businesscard D/MainActivity: onPause Method
2024-02-25 11:47:32.092 21045-21045/com.smorzhok.businesscard D/MainActivity: onStop Method
2024-02-25 11:47:32.093 21045-21045/com.smorzhok.businesscard D/MainActivity: onSaveInstanceState Method
2024-02-25 11:47:32.103 21045-21045/com.smorzhok.businesscard D/MainActivity: onDestroy Method
2024-02-25 11:47:32.146 21045-21045/com.smorzhok.businesscard D/MainActivity: OnCreate Method
2024-02-25 11:47:32.175 21045-21045/com.smorzhok.businesscard D/MainActivity: onStart Method
2024-02-25 11:47:32.176 21045-21045/com.smorzhok.businesscard D/MainActivity: onResume Method

логи приложения при "Сверните приложение, просмотрите логи."
2024-02-25 11:48:29.000 21446-21446/com.smorzhok.businesscard D/MainActivity: OnCreate Method
2024-02-25 11:48:29.030 21446-21446/com.smorzhok.businesscard D/MainActivity: onStart Method
2024-02-25 11:48:29.032 21446-21446/com.smorzhok.businesscard D/MainActivity: onResume Method
2024-02-25 11:48:31.404 21446-21446/com.smorzhok.businesscard D/MainActivity: onPause Method
2024-02-25 11:48:31.768 21446-21446/com.smorzhok.businesscard D/MainActivity: onStop Method
2024-02-25 11:48:31.771 21446-21446/com.smorzhok.businesscard D/MainActivity: onSaveInstanceState Method

логи приложения при "Напишите в методе onCreate() вызов метода finish(), просмотрите логи"
2024-02-25 11:49:29.263 21603-21603/com.smorzhok.businesscard D/MainActivity: OnCreate Method
2024-02-25 11:49:29.655 21603-21603/com.smorzhok.businesscard D/MainActivity: onDestroy Method

