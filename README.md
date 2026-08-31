<div align="center">
  <h1>Hey! Eu sou o Paulo Santos 👋☕</h1>
  <p><b>Dev Full Stack & Docente de TI</b> | Formando devs, compilando código e sobrevivendo ao ecossistema.</p>
  <p><i>"A vida não é um morango..." </i></p>

  <a href="https://paulo.cafe">
    <img src="https://img.shields.io/badge/Website-paulo.cafe-1E3A8A?style=Plastic&logo=google-chrome&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/paulocafee/">
    <img src="https://img.shields.io/badge/LinkedIn-Paulo_Santos-0A66C2?style=Plastic&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://instagram.com/paulo.cafee">
    <img src="https://img.shields.io/badge/Instagram-@paulo.cafee-E4405F?style=Plastic&logo=instagram&logoColor=white" />
  </a>
</div>

<br>

---

### Filosofia de Aula & Vida (Pode printar)

> 💬 **"Lerigo caraiii!"** — *Quando a build passa de primeira.*
> 
> 💬 **"Aqui vocês vão ter que confiar."** — *Antes de rodar aquele script sem testar.*
> 
> 💬 **"Gosto muito de vocês, mas gosto mais da minha casa."** — *Eu, pontualmente às 22:31.*

---

```php
<?php

require_once "PauloSantos.php";

class SobreMim extends Desenvolvedor {
    public string $nome = "Paulo H. Santos";
    public string $idade = "27 anos";
    public string $atuacao = "Docente & Dev. Full Stack";
    public string $empresaAtual = "Senac SP";
    public string $localizacao = "Americana / SP 🇧🇷";
    
    public array $frasesClassicas = [
        "A vida não é um morango",
        "Lerigo carae",
        "Aqui vocês vão ter que confiar",
        "Gosto muito de vocês mas gosto mais da minha casa"
    ];
}

class Skills extends Desenvolvedor {
    public array $linguagens = ["PHP", "JavaScript", "TypeScript", "C#", "Python", "Java"];
    public array $frameworks   = ["Laravel", "Slim", "ReactJS", "React Native", ".NET", "Spring Boot"];
    public array $bancoDeDados = ["MySQL", "Oracle", "MongoDB", "SQLite"];
    public array $devopsTools  = ["Docker", "Git", "Linux"];
}
