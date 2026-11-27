# Caixa Simples · HERYTA SOLUTIONS

Aplicação de caixa para pequenos comerciantes (vendas, stock, despesas, compras, dívidas, recibos).
Ficheiro único: `index.html`. Os dados ficam guardados no aparelho de cada utilizador.

## Publicar no GitHub Pages
1. Crie um repositório (por exemplo `caixa-simples`).
2. Carregue `index.html` na raiz do repositório.
3. Em **Settings > Pages**, escolha o ramo `main` e a pasta `/ (root)`.
4. O endereço fica `https://SEU-UTILIZADOR.github.io/caixa-simples/`.

## Guardar a versão antiga
Antes de substituir o `index.html`, crie uma etiqueta (release) `v1` com a versão atual.
Depois carregue a nova e crie a etiqueta `v2`. Para voltar atrás, republique a `v1`.

## Não publicar
A página de licenças (`caixa-simples-licencas-admin.html`) contém a chave privada que assina as licenças.
**Nunca a coloque no GitHub.** Só a chave pública está dentro do `index.html`, e isso é seguro.

## Notas
- PDF e Excel carregam bibliotecas da internet (cdnjs); precisam de ligação.
- O leitor de código de barras funciona nos navegadores que suportam `BarcodeDetector` (Chrome no Android).
