<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Домашнее задание к лекции «Введение в PHP»</title>
</head>
<body>
<?php
$userName = 'Натали';
$userAge = 22;
$userEMail = 'null@mail.ru';
$userCity = 'Москва';
$userInfo = 'Контент-менеджер';  ?>
<div>
    <h1>Страница пользователя Натали</h1>
    <p>Имя <?= $userName ?> </p>
    <p>Возраст <?= $userAge ?> </p>
    <p>Адрес электронной почты<p>
    <p> <a href="<?php echo'mailto:' . $userEMail ?>"><?php echo $userEMail ?></a> </p>
    <p> Город <?= $userCity ?> </p>
    <p>О себе <?= $userInfo ?> </p>
</div>
</body>
</html>
