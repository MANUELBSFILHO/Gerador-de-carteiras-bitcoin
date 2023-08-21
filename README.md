### Iniciando
## Instale o NODE
Dependencias
npm install bip39 bip32@2.0.6 bitcoinjs-lib --save

(bip39: Este é um pacote que implementa o BIP-39 (Bitcoin Improvement Proposal 39), que define um método para gerar chaves mnemônicas (frases de recuperação) a partir de uma sequência de palavras em inglês. Essas frases podem ser usadas para derivar chaves privadas e públicas para carteiras de criptomoedas. O BIP-39 é comumente utilizado para tornar a geração e recuperação de chaves mais amigável para os usuários, substituindo a necessidade de lidar diretamente com chaves complexas.

bip32@2.0.6: Este pacote é uma implementação do BIP-32 (Bitcoin Improvement Proposal 32), que define padrões para a criação de hierarquias de chaves determinísticas. Isso permite a geração de múltiplas chaves a partir de uma única semente, facilitando a organização de chaves para diferentes propósitos sem a necessidade de criar várias frases de recuperação. A versão especificada é 2.0.6.

bitcoinjs-lib: Este pacote é uma biblioteca que fornece funcionalidades para trabalhar com a rede Bitcoin. Ela inclui recursos para a criação e manipulação de transações, chaves públicas e privadas, assinaturas digitais e muito mais. Essa biblioteca é amplamente utilizada por desenvolvedores que desejam criar aplicativos que interagem com a rede Bitcoin.)

## Crie uma pasta src e crie o arquivo.js
para executar node .\nomedoarquivo.js

### Para inportar a carteira para um gerenciador.
baixe a versão conforme seu S.O.
https://electrum.org/#download