# SOL Coin - Token ERC20 na Blockchain Ethereum

Este projeto visa criar um **Token ERC-20** denominado **SOL Coin** utilizando contratos inteligentes (smart contracts) na blockchain Ethereum. O código foi obtido a partir do repositório do Professor Ricardo Zago da (DIO), disponível [neste link](https://github.com/relsi/web3-blockchain-classes/blob/main/token.sol).

## 📋 Objetivo

O objetivo deste projeto é criar um token chamado **SOL Coin**, que segue o padrão ERC-20, amplamente usado na Ethereum. Esse token poderá ser usado para transações na rede, integração em aplicativos descentralizados (dApps), e outras funcionalidades típicas de tokens.

## 🔧 Ferramentas Utilizadas

1. **Solidity**: Linguagem de programação usada para desenvolver contratos inteligentes na Ethereum.
2. **ChainIDE**: Plataforma de desenvolvimento baseada em navegador, utilizada para compilar e implantar o contrato na blockchain.
  - [Link para o ChainIDE](https://chainide.com/s/ethereum/)
   
3. **Google Cloud Web3 Faucet (Sepolia)**: Utilizado para obter **ETH** para as taxas de transação durante os testes na rede de testes **Sepolia**.
  - [Link para o Faucet Google Cloud Web3](https://cloud.google.com/application/web3/faucet/ethereum/sepolia)
   
4. **MetaMask**: Carteira digital usada para interagir com a blockchain e gerenciar tokens.
  - [Link para o MetaMask](https://metamask.io/)

## 🛠 Funcionalidades do Contrato

### Estrutura do Token

- **Nome do Token**: SOL Coin
- **Símbolo**: SOL
- **Decimais**: 2
- **Supply Total**: 1.000.000 tokens

### Funções Principais

1. **totalSupply**: Retorna o total de tokens disponíveis.
2. **balanceOf**: Retorna o saldo de um endereço específico.
3. **transfer**: Transfere tokens de uma conta para outra.
4. **approve**: Autoriza um terceiro a gastar tokens em nome do proprietário.
5. **allowance**: Retorna a quantidade de tokens que um terceiro pode gastar.
6. **transferFrom**: Transfere tokens de uma conta autorizada para outra.

### Eventos

- **Transfer**: Evento que é emitido sempre que tokens são transferidos.
- **Approval**: Evento que é emitido quando um proprietário de tokens aprova um terceiro para gastar em seu nome.

## 🚀 Segue o Passo a Passo para Executar o Código

### 1. Compilar e Implante o Contrato

- Abra o **ChainIDE** e crie um novo projeto.
- Cole o código do arquivo **token.sol** no editor.
- Selecione o compilador **Solidity** versão 0.8.7.
- Conecte a sua carteira **MetaMask** à rede de testes **Sepolia**.
- Implante o contrato na rede de teste.

### 2. Obtenção de Faucet

- Acesse o [Google Cloud Web3 Faucet](https://cloud.google.com/application/web3/faucet/ethereum/sepolia) e solicite ETH para a rede de testes **Sepolia**.
- **Atenção**: Recomendo começar a acumular **faucet** antes de iniciar o projeto, pois há um limite de moedas disponíveis. Uma vez atingido esse limite, normalmente será necessário aguardar **24 horas** para realizar uma nova transferência.

### 3. Teste do Contrato

- Realize o deploy no **ChainIDE**.
- Depois verifique seu saldo inicial de **SOL Coin** usando o **MetaMask**.
- Caso não apareça automaticamente. Pode inserir manualmente, copiando o endeço do contrato e inserindo na opção **Importar tokens** do **MetaMask**.
- Agora divirta-se. Realize transferências de tokens, aprove terceiros para gastar em seu nome.

## 📚 Referências

- **ERC-20**: [Padrão de Token ERC-20](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/)
- **MetaMask**: [Documentação do MetaMask](https://docs.metamask.io/)
- **ChainIDE**: [Documentação do ChainIDE](https://chainide.gitbook.io/chainide/)
- **Google Cloud Web3 Faucet**: [Faucets do Google Cloud Web3](https://cloud.google.com/application/web3/faucet/ethereum/sepolia)