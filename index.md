<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" type="text/css" href="css/style.css">
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/5ZPW3AM7VJAAdH7ioWUmEJCcapKHEbsQ6SlHL_YdwOq9aCjTjsuLV4ZNENvyoIoAlO45k14xcTeuUf9cXxTC=w1937-h985" />
  <title>Home</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto+Mono&display=swap');

    :root {
      --font: "Roboto Mono";
      --background: #0f0e17;
      --foreground: #fffffe;
      --pink: #e53170;
      --red: #f25f4c;
      --orange: #ff8906;
      --branch: 1px solid #a7a9be;
    }

    html {
      font-size: 18px;
    }

    body {
      background: var(--background);
    }

    .container {
      position: absolute;
      top: 50%;
      left: 45%;
      transform: translate(-50%, -50%);
    }

    .prompt {
      font-family: var(--font);
      color: var(--foreground);
    }

    .prompt~.prompt {
      padding: 1.5rem 0 0.3125rem;
    }

    span {
      color: var(--pink);
    }

    h1 {
      display: inline;
      font-family: var(--font);
      font-size: 1rem;
      font-weight: normal;
      color: var(--red);
    }

    .tree>ul {
      margin: 0;
      padding-left: 1rem;
    }

    ul {
      list-style: none;
      padding-left: 2.5rem;
    }

    li {
      position: relative;
    }

    li::before,
    li::after {
      content: "";
      position: absolute;
      left: -0.75rem;
    }

    li::before {
      border-top: var(--branch);
      top: 0.75rem;
      width: 0.5rem;
    }

    li::after {
      border-left: var(--branch);
      height: 100%;
      top: 0.25rem;
    }

    li:last-child::after {
      height: 0.5rem;
    }

    a {
      font-family: var(--font);
      font-size: 1rem;
      color: var(--foreground);
      text-decoration: none;
      outline: none;
    }

    a:hover {
      color: var(--background);
      background: var(--orange);
    }

    form h1 {
      padding-left: 0.125rem;
    }

    input {
      font-family: var(--font);
      font-size: 1rem;
      color: var(--foreground);
      background-color: var(--background);
      border: none;
    }
  </style>
</head>

<body>
  <div class="container">
    <div class="prompt">[<span>burg0</span>@<span>home</span> ~]$ tree</div>
    <div class="tree">
      <h1>.</h1>
      <ul>
        <li>
          <h1>utility</h1>
          <ul>
            <li><a href="https://tinylist.app/">tinylist</a></li>
            <li><a href="https://privacytools.io/">privacytools</a></li>
            <li><a href="https://mail.google.com/">gmail</a></li>
            <li><a href="https://mail.protonmail.com/">protonmail</a></li>
          </ul>
        </li>
        <li>
          <h1>streaming</h1>
          <ul>
            <li><a href="https://www.netflix.com/browse">netflix</a></li>
            <li><a href="https://www.primevideo.com/">prime</a></li>
            <li><a href="https://www.youtube.com/">youtube</a></li>
            <li><a href="https://www.twitch.tv/">twitch</a></li>
          </ul>
        </li>
        <li>
          <h1>varie</h1>
          <ul>
            <li><a href="https://www.reddit.com/">reddit</a></li>
            <li><a href="https://www.amazon.it/">amazon</a></li>
            <li><a href="https://www.allkeyshop.com/">allkeyshop</a></li>
            <li><a href="https://streamelements.com/">streamelements</a></li>
			<li><a href="https://unsplash.com/">unsplash</a></li>
          </ul>
        </li>
      </ul>
    </div>
    <div class="prompt">[<span>burg0</span>@<span>home</span> ~]$ qwant</div>
    <form action="https://qwant.com/" method="GET" autocomplete="off">
      <h1>search: </h1>
      <input type="text" name="q" autofocus="autofocus">
    </form>
  </div>
</body>

</html>
