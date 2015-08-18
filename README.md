# Tradução com JavaScript

#### Tradução de conteúdo em linha usando apenas JavaScript (sem jQuery)

**Modo de Uso**
* Defina a classe que deseja usar como tradução (Padrão `tdr`);
* Insira o arquivo de tradução no rodapé do seu site;
* Inicie o objeto de tradução passando os dados em formato de `json`;
* Pronto para uso.

**Exemplo de uso**
* Classe de tradução (Padrão `tdr`):
```html
<div class="tdr">Conteúdo à ser traduzido</div>
```

* Objeto de tradução com o conteúdo:
```javascript
Traducao({"Conteúdo à ser traduzido": "Content to be translated");
```
...e pronto, o conteúdo já será traduzido. Você pode definir vários idiomas e chama-los para cada ocasião.
Simples e super usual.
