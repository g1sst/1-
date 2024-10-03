# HTML 5 Страница с маркированным списком гиперссылок и формой

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Гиперссылки и форма</title>
</head>
<body>
    <h1>Маркированный список гиперссылок</h1>
    <ul>
        <li><a href="http://kubsu.ru">Главная страница сайта kubsu.ru</a></li>
        <li><a href="https://kubsu.ru">Главная сайта kubsu.ru в протоколе HTTPS</a></li>
        <li><a href="https://kubsu.ru"><img style="width: 400 px;" src="https://kubsu.ru/lib/images/Group3288.png" alt="Ссылка-изображение" /></a></li>
        <li><a href="https://www.kubsu.ru/index.php">Сокращенная ссылка на внутреннюю страницу</a></li>
        <li><a href="/">Сокращенная ссылка на главную страницу</a></li>
        <li><a href="#fragment">Ссылка на фрагмент текущей страницы</a></li>
        <li><a href="/page?param1=value1&param2=value2&param3=value3">Ссылка с тремя параметрами в URL</a></li>
        <li><a href="/page?id=123">Ссылка с параметром id в URL</a></li>
        <li><a href="page.html">Относительная ссылка на страницу в текущем каталоге</a></li>
        <li><a href="about/page.html">Относительная ссылка на страницу в каталоге about</a></li>
        <li><a href="../page.html">Относительная ссылка на страницу в каталоге уровнем выше текущего</a></li>
        <li><a href="../../page.html">Относительная ссылка на страницу в каталоге двумя уровнями выше</a></li>
        <li><p>Контекстная <a href="https://example.com">ссылка в тексте абзаца</a>.</p></li>
        <li><a href="https://github.com/g1sst">Ссылка на фрагмент страницы стороннего сайта</a></li>
        <li>
            <img src="" usemap="#map">
            <map name="map">
                <area shape="rect" coords="34,44,270,350" href="https://example.com/rect-link" alt="Ссылка в прямоугольной области" />
                <area shape="circle" coords="337,300,44" href="https://example.com/circle-link" alt="Ссылка в круглой области" />
            </map>
        </li>
        <li><a href="#">Ссылка с пустым href</a></li>
        <li><a>Ссылка без href</a></li>
        <li><a rel="nofollow" href="https://example.com">Ссылка, по которой запрещен переход поисковикам</a></li>
        <li><a rel="noindex" href="https://example.com">Запрещенная для индексации поисковиками ссылка</a></li>
        <li>
            <ol>
                <li><a href="http://example.com" title="Ссылка 1">Ссылка 1</a></li>
                <li><a href="http://example.com" title="Ссылка 2">Ссылка 2</a></li>
                <li><a href="http://example.com" title="Ссылка 3">Ссылка 3</a></li>
            </ol>
        </li>
        <li><a href="ftp://username:password@ftp.example.com/file.txt">Ссылка на файл на сервере FTP с авторизацией</a></li>
    </ul>

    <h2>Форма</h2>
    <form action="/"
    method="POST">

    <label>
      ФИО:<br />
      <input name="fio"
      placeholder="Введите ФИО" />
    </label><br />

    <label>
        Номер телефона:<br />
        <input name="field-phone"
          type="tel"
          placeholder="Введите номер телефона" />
      </label><br />

    <label>
       Email:<br />
      <input name="field-email"
        type="email"
        placeholder="Введите вашу почту" />
    </label><br />

    <label>
      Введите дату рождения:<br />
      <input name="field-date"
        type="date" />
    </label><br />

    Пол:<br />
    <label><input type="radio"
      name="radio-group1" value="Мужской" />
      Мужской</label>
    <label><input type="radio"
      name="radio-group1" value="Женский" />
      Женский</label><br />

      <label>
        Любимый язык программирования:
        <br />
        <select name="field-name-4[]"
          multiple="multiple">
          <option value="Значение1">Pascal</option>
          <option value="Значение2">C</option>
          <option value="Значение3">C++</option>
          <option value="Значение4">JavaScript</option>
          <option value="Значение5">PHP</option>
          <option value="Значение6">Python</option>
          <option value="Значение7">Java</option>
          <option value="Значение8">Haskel</option>
          <option value="Значение9">Clojure</option>
          <option value="Значение10">Prolog</option>
          <option value="Значение11">Scala</option>
        </select>
      </label><br />
    <label>
        Биография:<br />
        <textarea name="field-name-2"></textarea>
      </label><br />



    <br />
    <label><input type="checkbox" checked="checked"
      name="check-1" />
    С контрактом ознакомлен (а)</label><br />

    <input type="submit" value="Сохранить" />
  </form>
</body>
</html>

Конец HTML кода
