# Como subir este site no GitHub pelo celular

Repositório:
chatgptcompartilhadocwb-creator/imp-rio-

## Arquivos que precisam ficar na raiz do repositório
- index.html
- styles.css
- script.js
- vercel.json
- robots.txt
- README.md
- pasta assets/

## Pelo navegador do celular
1. Abra o repositório no GitHub.
2. Toque em **Add file** > **Upload files**.
3. Extraia este ZIP no celular antes do envio.
4. Envie os arquivos da raiz e a pasta `assets`.
5. Confirme o commit na branch `main`.

IMPORTANTE:
Não envie a pasta externa `imperio-site-final` inteira como uma subpasta.
O arquivo `index.html` deve aparecer diretamente na página principal do repositório.

## Depois
Na Vercel:
1. Add New > Project.
2. Importe o repositório `imp-rio-`.
3. Framework Preset: Other.
4. Root Directory: deixe na raiz.
5. Deploy.

O projeto é estático e não exige npm, build command ou variáveis de ambiente.
