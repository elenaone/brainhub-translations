# brainhub-translations
## Инструкция по работе с GitHub
Для работы с GitHub нужно скачать приложение GitHub Desktop с сайта https://desktop.github.com/ и установить его.
После регистрации в GitHub вы получите ссылку на репозиторий с переводами. На странице с переводами, выглядящей примерно как ниже, нужно найти кнопку “Fork”
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image1.png)
Нажимаем и выбираем какому пользователю добавляем репозиторий (по умолчанию вашему):
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image2.png)
Наблюдаем картину добавления репозитория в ваш аккаунт:
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image3.png)
После чего попадаем на страницу репозитория уже в вашем аккаунте. Ищем кнопку “Clone or download”(1). Нажимаем на нее и копируем ссылку на репозиторий(2):
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image4.png)
После чего открываем приложение GitHub Desktop и в меню “File” выбираем пункт “Clone repository”. В открывшемся окне выбираем вкладку “URL” и вставляем в строке скопированную ранее ссылку:
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image5.png)
Нажимаем кнопку “Clone” и репозиторий скачивается к вам на компьютер. После чего откроется окно приложения: 
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image6.png)
Теперь можно делать изменения в файлах. Для примера возьмем текстовый файл first в каталоге локального репозитория:
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image7.png)
Сохраним изменения.
В приложении GitHub увидим, что есть изменения в файле, который мы только что редактировали:
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image8.png)
Для того, чтобы сохранить и отправить результаты изменений в удаленном репозитории (чтобы другие участники тоже могли видеть изменения), достаточно сделать commit и pull. Для этого в приложении есть панель слева, на которой перечислены все файлы, которые подверглись изменениям (1):
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image9.png)
Для сохранения результатов, нужно заполнить внизу (2) поля комментариями (описание изменений) и нажать “Commit to dev”. Сразу после этого нужно отправить изменения на удаленный репозиторий с помощью команды меню “Repository” -> “Push”:
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image10.png)
Все, теперь ваши изменения есть только в вашем репозитории.
Для того, чтобы ваши изменения увидели все участники сообщества, нужно сделать слияние вашего репозитория с основным. Для этого достаточно в меню “Branch” выбрать пункт “Create pull request”. Вас перебросит на страницу создания запроса на слияние, где нажимаем кнопку “Create pull request”:
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image11.png)
Попадаем в следующее окно, информация заполняется автоматически, но можно и дополнить и нажимаем еще раз кнопку “Create pull request”
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image12.png)
В следующем окне можем написать комментарий членам команды, если что-то вдруг забыли. И ожидаем Merge:
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image13.png)
Когда сделают слияние вашего репозитория с основным, то запрос примет такой вид:
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image14.png)
Теперь можно нажать кнопку закрытия запроса (“Close pull request”). И все, дело сделано.
![alt text](https://raw.githubusercontent.com/ewindt/brainhub-translations/master/manuals/images/image15.png)
Теперь вы достаточно подготовлены для работы.