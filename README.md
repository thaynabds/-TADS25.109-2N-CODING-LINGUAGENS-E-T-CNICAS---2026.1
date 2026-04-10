# ATIVIDADE - AULA 07/04/2026

**Aluna:** Thayná Batista da Silva  
**Unidade Curricular:** TADS25.109/2N - CODING: LINGUAGENS E TÉCNICAS  
**Turma/Período:** 2026.1

```markdown
# ATIVIDADE - AULA 07/04/2026

**Aluna:** Thayná Batista da Silva  
**Unidade Curricular:** TADS25.109/2N - CODING: LINGUAGENS E TÉCNICAS  
**Turma/Período:** 2026.1

---

## 📁 ARQUIVOS DA ATIVIDADE

1. `formulario.html`
2. `lista.html`
3. `mozilla.html`

---

## 1. FORMULÁRIO DE PESQUISA DE FILMES

**Arquivo:** `formulario.html`

```html
<!DOCTYPE html>
<html>
<head>
    <title>Pesquisa de Filmes</title>
    <style>
        body {
            background: purple;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            font-family: Arial;
        }
        .form {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 5px 5px 15px black;
            width: 400px;
        }
        h1 {
            text-align: center;
        }
        input, label {
            margin: 8px 0;
            display: block;
        }
        .grupo {
            margin-bottom: 15px;
        }
        .inline {
            display: inline;
            margin-right: 10px;
        }
        button {
            padding: 10px 20px;
            margin: 10px 5px;
            cursor: pointer;
        }
        button:hover {
            background: purple;
            color: white;
        }
    </style>
</head>
<body>
    <div class="form">
        <h1>PESQUISA DE FILMES</h1>
        
        <form>
            <div class="grupo">
                <label>NOME:</label>
                <input type="text" placeholder="Digite seu nome">
            </div>
            
            <div class="grupo">
                <label>IDADE:</label>
                <input type="number" placeholder="Sua idade">
            </div>
            
            <div class="grupo">
                <label>GÊNERO DE FILMES FAVORITOS:</label>
                <label class="inline"><input type="checkbox"> Ação</label>
                <label class="inline"><input type="checkbox"> Romance</label>
                <label class="inline"><input type="checkbox"> Comédia</label>
                <label class="inline"><input type="checkbox"> Nacional</label>
                <label class="inline"><input type="checkbox"> Outros</label>
            </div>
            
            <div class="grupo">
                <label>Quantos filmes por semana?</label>
                <label class="inline"><input type="radio" name="qtd"> 0</label>
                <label class="inline"><input type="radio" name="qtd"> 1</label>
                <label class="inline"><input type="radio" name="qtd"> 2</label>
                <label class="inline"><input type="radio" name="qtd"> Mais de 2</label>
            </div>
            
            <button type="submit">ENVIAR</button>
            <button type="reset">LIMPAR</button>
        </form>
    </div>
</body>
</html>
```

---

## 2. LISTA DE FILMES POR GÊNERO

**Arquivo:** `lista.html`

```html
<!DOCTYPE html>
<html>
<head>
    <title>Lista de Filmes</title>
</head>
<body>
    <h1>Lista de FILMES</h1>
    
    <ol>
        <li>Ação
            <ol type="a">
                <li>Cidade Perdida</li>
                <li>Agente Oculto</li>
            </ol>
        </li>
        
        <li>Desenhos animados
            <ol type="a">
                <li>Luck</li>
                <li>Mundo Estranho</li>
                <li>A era do Gelo</li>
            </ol>
        </li>
        
        <li>Ficção
            <ol type="a">
                <li>Avatar</li>
                <li>A origem</li>
                <li>Jurassic Park</li>
                <li>Star Wars</li>
            </ol>
        </li>
        
        <li>Terror
            <ol type="a">
                <li>Órfã</li>
                <li>Sorria</li>
            </ol>
        </li>
    </ol>
</body>
</html>
```

---

## 3. PÁGINA "MOZILLA IS COOL"

**Arquivo:** `mozilla.html`

```html
<!DOCTYPE html>
<html>
<head>
    <title>Mozilla is cool</title>
    <style>
        p {
            color: red;
        }
    </style>
</head>
<body>
    <img src="https://www.mozilla.org/media/img/logos/firefox/logo-lg-high-res.3f13e9d82f5a.png" width="100">
    
    <h1>Mozilla is cool</h1>
    
    <p>At Mozilla, we're a global community of technologists, thinkers, and builders working together to keep the Internet alive and accessible, so people worldwide can be informed contributors and creators of the Web.</p>
    
    <p>We believe this act of human collaboration across an open platform is essential to individual growth and our collective future.</p>
    
    <p>Read the <a href="https://www.mozilla.org/manifesto/" target="_blank">Mozilla Manifesto</a> to learn even more about the values and principles that guide the pursuit of our mission.</p>
    
    <ul>
        <li>technologists</li>
        <li>thinkers</li>
        <li>builders</li>
    </ul>
</body>
</html>
```

---

## 🚀 COMO EXECUTAR

1. Copie cada código acima
2. Cole em arquivos separados com os nomes indicados
3. Abra cada arquivo no navegador

---

## ✅ ENTREGA

- **Data:** 14/04/2026

---

**Fim do README**
```

---

Agora sim! O README contém **todos os códigos completos** dentro dele. ✅
