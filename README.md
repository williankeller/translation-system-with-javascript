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
Tradutor({"Conteúdo à ser traduzido": "Content to be translated");
```
O método acima é a forma mais simples para se traduzir um conteúdo inline.
Basta inserir o conteúdo de base e o conteúdo de tradução.

* Tradução usando conteúdo dinâmico (Padrão `%`):*
```html
<div class="tdr">Conteúdo JavaScript ser traduzido sem jQuery</div>
```
* Objeto de tradução com o conteúdo dinâmico:*
```javascript
Tradutor({"Conteúdo % ser traduzido sem %": "Content % to be translated without %");
```
O método acima, é usado para fazer a substituição de uma conteúdo dinâmico, isto é, as palavras substituidas por `%` serão mantidas.
No exemplo citado, `Conteúdo % ser traduzido sem %` imprimirá `Conteúdo JavaScript ser traduzido sem jQuery` as palavras `JavaScript`e `jQuery` não serão alteradas.

Isso vale para números, textos e/ou caracteres especiais.

...e pronto, o conteúdo já será traduzido. Você pode definir vários idiomas e chama-los para cada ocasião.
Simples e super usual.
