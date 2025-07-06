
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Es un loco este archivo</title>
</head>
<style>
    body {
        background-image: url('https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExeTkwenZld3c5eWxzaDIwaHJqMTNxOGtxeHJ3NDBqODMwMzRzZ2V4eiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/39998EKTZQkt0Xhgi5/giphy.gif');
        background-size: cover;
        color: #f7f3f0;
        font-family: Georgia, 'Times New Roman', Times, serif;
        text-align: center;
        padding: 50px;
    }
    button
    {
        background-color: #04021b;
        color: #f0f0f0;
        border: 2px solid #262170;
        font-family: Georgia, 'Times New Roman', Times, serif;
        font-size: 1.5em;
        padding: 10px 20px;
        margin: 10px;
    }
    
    button:hover {
        background-color: #0c054d;
        color: #04021b;
        cursor: pointer;
        transform: scale(1.05);
    }
    button:focus {
        outline: none;
        box-shadow: 0 0 5px #740606;
    }
    button:active {
        background-color: #961212;
        color: #f0f0f0;
    }

    .card {
        background-color: #08074991;
        border-radius: 25px;
        box-shadow: 4 6px 8px rgba(48, 5, 5, 0.815);
        margin: 10px;
        padding: 25px;
        display: inline-block;
        transition: transform 0.3s ease;
        }
    

    h1 {
        color: #f4f3f5;
        font-family: Georgia, 'Times New Roman', Times, serif;
        text-align: center;
        padding: 10px;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        font-size: 2.5em;
    }   
    h2 {
        color: #f0f0f0;
        font-family: Georgia, 'Times New Roman', Times, serif;
        text-align: center;
        padding: 10px;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    }
</style>
</head>
<body>
  <h1>¿Queres salir por ahi conmigo?</h1>
  <div>
     <button onclick="alert('Apreta boton Siguiente')">Si</button>
    </a>
      <a href="https://www.youtube.com/watch?v=ZJoW95Y1Caw">
        <button>No</button>
    </a>
   </div>
  
    
  <div class="card">
        <h2>¿Qué día?</h2>
        <button onclick="alert('17:30HS')">Lunes</button>
        <button onclick="alert('17:00HS')">Martes</button>
        <button onclick="alert('18:00HS')">Miércoles</button>
        <button onclick="alert('17:00HS')">Jueves</button>
        <button onclick="alert('17:30HS')">Viernes</button>
        <button onclick="alert('20:00HS')">Sábado</button>
  </div>
    
   <div>
      <a href="lugares.html">
        <button>Siguiente</button>
    </div>

  </body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lugares</title>
</head>
 <style>
    body {
        background-image: url('https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExdTB3c2M1dWF0YmxzZWY5c29rcXZwMG4xM2UwcDF4bTNlczJobjAzeiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/h9b9wAieMM0cgbzaPn/giphy.gif');
        background-size: cover;
        color: #f7f3f0;
        font-family: Georgia, 'Times New Roman', Times, serif;
        text-align: center;
        padding: 50px;
    }
    button {
        background-color: #04021b;
        color: #f0f0f0;
        border: 2px solid #f0f0f0;
        font-family: Georgia, 'Times New Roman', Times, serif;
        font-size: 1.5em;
        padding: 10px 20px;
        margin: 10px;
    }
    button:hover {
        background-color: #4d1305;
        color: #04021b;
        cursor: pointer;
        transform: scale(1.05);
    }
    button:focus {
        outline: none;
        box-shadow: 0 0 5px #751508;
    }
    button:active {
        background-color: #961212;
        color: #f0f0f0;
    }
    .card {
        background-color: #08074991;
        border-radius: 25px;
        box-shadow: 4px 6px 8px rgba(48, 5, 5, 0.815);
        margin: 10px auto;
        padding: 25px;
        display: inline-block;
    }
    h1 {
        color: #f4f3f5;
        font-family: Georgia, 'Times New Roman', Times, serif;
        text-align: center;
        padding: 10px;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        font-size: 2.5em;
    }
 </style>
</head>
<body>
    <h1>¿Dónde quieres ir?</h1>
    <div class="card">
        <h2 id="Lugares">Lugares</h2>
        <button onclick="alert('NO ES NADA')">Plaza</button>
        <button onclick="alert('MAS')">Caminar</button>
        <button onclick="alert('QUE SALIDA')">Centro</button>
        <button onclick="alert('DE AMUGOS')">Cine</button>
    </div>
        <div>
            <a href="https://www.google.com/search?q=plaza+pringles+villa+mercedes&sca_esv=78f075c4f91bed6c&sxsrf=AE3TifOaXzqE0UAe4JS_lerGXqzFMTCefw%3A1751808769615&ei=AXtqaNqoJezd1sQPj-fKyAY&gs_ssp=eJwFwUsKgCAUAEDa1hkCN639lJodoVs89SGChmiEePpm5oUGyl8_bN4Nm66NdSM9V6CU0Faag_GLdYXGnha1A4EanLvXkmAAKTU-IWEjX0wJSMbq0GP7AfekGk8&oq=plaza+pringles+villa+me&gs_lp=Egxnd3Mtd2l6LXNlcnAiF3BsYXphIHByaW5nbGVzIHZpbGxhIG1lKgIIADILEC4YgAQYxwEYrwEyBhAAGBYYHjICECYyCBAAGIAEGKIEMgUQABjvBTIIEAAYogQYiQUyGhAuGIAEGMcBGK8BGJcFGNwEGN4EGOAE2AEBSP5bUOoHWJRKcAV4AZABAZgB5wGgAYUiqgEGMS4yOC4zuAEByAEA-AEBmAImoALzPcICChAAGLADGNYEGEfCAgQQIxgnwgILEAAYgAQYsQMYgwHCAgUQABiABMICExAuGIAEGMcBGCcYigUYjgUYrwHCAggQABiABBixA8ICBBAAGAPCAg4QABiABBixAxiDARiKBcICChAAGIAEGBQYhwLCAhAQLhiABBgUGIcCGMcBGK8BwgIREC4YgAQYxwEYmAUYmQUYrwHCAgsQABiABBiSAxiKBcICIBAuGIAEGMcBGJgFGJkFGK8BGJcFGNwEGN4EGOAE2AEBwgIIEAAYgAQYyQPCAgcQABiABBgNwgINEC4YgAQYxwEYDRivAcICEBAuGIAEGBQYxwEYhwIYrwHCAgUQIRigAZgDAIgGAZAGCLoGBggBEAEYFJIHEDUuMjUuMy4wLjMuMS4wLjGgB5HEA7IHBjAuMjUuM7gHpCDCBwkwLjUuMjIuMTHIB_gB&sclient=gws-wiz-serp">Plaza Pringles</a>
            <br><br>
            <a href="https://www.google.com/search?q=plaza+de+la+salud+villa+mercedes&sca_esv=78f075c4f91bed6c&sxsrf=AE3TifOK4k3s4j19Zxv6fP72_D3iHYZJWA%3A1751808324722&ei=RHlqaPzrK5L25OUPj7KguQ0&gs_ssp=eJwNxkEKgCAQAEC6Bv1hL51ztTR9Qr9Y3DUCgyiS8vU1p2m7YR0QU02p-PKqJvTq8ROjJZtwtJomy0E96LQSjRjNOBvj9AJHpkrAApngonwzlC3_3-WMwnJ9XWUamw&oq=plaza+de+la+salud+villa+mercedes&gs_lp=Egxnd3Mtd2l6LXNlcnAiIHBsYXphIGRlIGxhIHNhbHVkIHZpbGxhIG1lcmNlZGVzKgIIADIOEC4YgAQYsAMYxwEYrwEyCxAAGIAEGLADGKIEMggQABiwAxjvBTILEAAYgAQYsAMYogRI6g1QAFgAcAF4AJABAJgB1AWgAdQFqgEDNi0xuAEByAEAmAIBoAIJmAMAiAYBkAYEkgcBMaAHuwayBwC4BwDCBwMyLTHIBwc&sclient=gws-wiz-serp">Plaza de la Salud</a>
            <br><br>
            <a href="https://www.google.com/search?q=plaza+pedernera+villa+mercedes&sca_esv=78f075c4f91bed6c&sxsrf=AE3TifMavr2cobhporY1uaTzE9JqMg-7wQ%3A1751808801007&ei=IXtqaLsb0NbWxA_S4575Cg&oq=plaza+pedernera+&gs_lp=Egxnd3Mtd2l6LXNlcnAiEHBsYXphIHBlZGVybmVyYSAqAggAMgUQABiABDIFEAAYgAQyAhAmMgYQABgWGB4yAhAmMggQABiABBiiBDIIEAAYgAQYogRInkJQ5h5YkTNwAngAkAEAmAHlAaAB-BOqAQYwLjE0LjK4AQHIAQD4AQGYAhKgAssVqAIQwgINEAAYgAQYsAMYQxiKBcICDhAuGIAEGLADGMcBGK8BwgILEAAYgAQYsAMYogTCAg0QLhjHARgnGOoCGK8BwgIHECMYJxjqAsICChAjGPAFGCcY6gLCAhMQABiABBhDGLQCGIoFGOoC2AEBwgIQEAAYAxi0AhjqAhiPAdgBAcICEBAuGAMYtAIY6gIYjwHYAQHCAgQQIxgnwgITEC4YgAQYxwEYJxiKBRiOBRivAcICChAjGIAEGCcYigXCAgoQABiABBhDGIoFwgIQEC4YgAQYQxjHARiKBRivAcICCBAAGIAEGLEDwgIKECMY8AUYJxjJAsICERAuGIAEGMcBGJgFGJkFGK8BwgILEC4YgAQYxwEYrwHCAiAQLhiABBjHARiKBRiOBRivARiXBRjcBBjeBBjgBNgBAcICDhAuGIAEGMcBGI4FGK8BwgIKEAAYgAQYFBiHAsICBxAAGIAEGArCAggQABgWGAoYHpgDGPEFMViyc4iIdbCIBgGQBgS6BgYIARABGAGSBwYyLjEyLjSgB8WSArIHBjAuMTIuNLgHpxXCBwgyLTMuMTQuMcgHwwE&sclient=gws-wiz-serp">Plaza Pedernera</a>
   </div>
    <div>
        <a href="https://wa.me/5492657675467?text=Quiero%20ir%20a%20la%20Plaza%20Salud" target="_blank">
  <button>Plaza Salud</button>
</a>

<a href="https://wa.me/5492657675467?text=Me%20gustaría%20ir%20al%20Plaza%20Pringles" target="_blank">
  <button>Plaza Pringles</button>
</a>

<a href="https://wa.me/5492657675467?text=Vamos%20al%20Plaza%20Pedernera!" target="_blank">
  <button>Plaza Pedernera</button>
</a>

   </div>
   <a href="https://wa.me/5492657675467?text=¡SI Acepto bro!" target="_blank">
        <button>Acepto</button>
      </a>
</body>
</html>
