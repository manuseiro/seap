# A base de empreendimento BACEN está desatualizada

Procedimento destina a clientes e projetista que utilizam as planilha de projeto disponibilizada pelo Banco do Nordete. Segue abaixo passos 
para correção de critica apresentada ao utilizar planilhas de projetos disponivel pelo Banco do Nordeste.

<h1 align="center">
  <img alt="CriticaBacen" title="#CriticaBacen" src="./img/Critica.png" />
</h1>

### NOTA: 
Utilize este aplicativo somente com o Microsoft Excel, na plataforma de 32 bits, em qualquer versão a partir do Excel 2007. 
Caso possua a versão 64 bits instalada, é necessário que seja feita a desinstalação do office 64 bits e instalado o Office 32 bits.

Recomendamos que seja reiniciado a maquia após a desisntalação do Office para em seguida efetuar a instalação novamente.

### PRÉ-REQUISITO:
Antes de começar, você vai precisar ter instalado em sua máquina um dos pacote [Office 32 bits](https://www.microsoft.com/pt-br/microsoft-365/microsoft-office) de qualquer versão apartir do Office 2007.

Estar utilizando a ultima versão do [Componente Empreendimento BACEN](https://www.bnb.gov.br/aplicativos-para-elaboracao-de-propostas) (Versão: 23/07/2020) disponivel no site bnb.gov.br.

### INSTALAÇÃO:
1. Copie os arquivos (PreencheEmpreendimento.dll, SPR32D30.DLL e SPR32X30.OCX) para dentro do diretorio de instalação do 
Componente Empreendimento BACEN (C:\SISTEMAS\COMPONENTES\PreencheEmpreendimento) substituindo os presentes.
<h1 align="center">
  <img alt="ArquivoCopia" title="#ArquivosCopia" src="./img/ArquivosCopia.png" />
</h1>

2. Feche o programa Microsoft Excel, caso esteja com ele aberto.

3. Execulte o CMD (Prompt de Comando) como Administrador.

4. Acesse o diretorio do Componente pelo comando abaixo:

<h1 align="center">
  <img alt="DiretorioPreencheEmpreendimento" title="#DiretorioPreencheEmpreendimento" src="./img/DiretorioPreencheEmpreendimento.png" />
</h1>

```bash
cd C:\SISTEMAS\COMPONENTES\PreencheEmpreendimento
```

5. Digite o comando abaixo e de Enter, será apresentado tela de confirmação. Clique em OK.

<h1 align="center">
  <img alt="PreencheEmpreendimento" title="#PreencheEmpreendimento" src="./img/PreencheEmpreendimento.dll.png" />
</h1>

```bash
regsvr32 PreencheEmpreendimento.dll
```

6. Repita o procedimento com o comando abaixo.
<h1 align="center">
  <img alt="SPR32X30" title="#SPR32X30" src="./img/SPR32X30.OCX.png" />
</h1>

```bash
regsvr32 SPR32X30.OCX
```

Pronto! com isso as planilhas de Projeto não apresentaram mais a critica.

### TECNOLOGIAS

- [Office 365 - 32 Bits](https://www.microsoft.com/pt-br/microsoft-365/microsoft-office)
- [Componente Empreendimento BACEN](https://www.bnb.gov.br/aplicativos-para-elaboracao-de-propostas) (Versão: 23/07/2020)
- [Planilha Pronaf](https://www.bnb.gov.br/aplicativos-para-elaboracao-de-propostas) (Versão: 23/02/2021)
- regsvr32




