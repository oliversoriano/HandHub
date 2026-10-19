# 🤝 HandHub

**HandHub** é um aplicativo desktop para Windows que facilita o dia a dia do **time de suporte** e dos **clientes durante o período de implantação** de sistema, reunindo em um só lugar o acompanhamento e a comunicação dessa fase.

Este repositório é o **canal de distribuição** do aplicativo: aqui ficam o instalador e o arquivo que o HandHub consulta para saber se há uma nova versão.

[![Versão](https://img.shields.io/badge/vers%C3%A3o-1.3.1-4f46e5)](versao.json)
![Plataforma](https://img.shields.io/badge/plataforma-Windows-0078D6?logo=windows&logoColor=white)

## ⬇️ Download

Baixe a versão mais recente na página de **[Releases](https://github.com/oliversoriano/HandHub-Releases/releases/latest)** e execute o `HandHub.exe`.

> No primeiro uso, o Windows SmartScreen pode exibir um aviso por o aplicativo não ser assinado digitalmente. Clique em **Mais informações → Executar assim mesmo**.

## 🔄 Atualização automática

O HandHub verifica sozinho se existe uma versão nova. Ao abrir, o aplicativo lê o arquivo [`versao.json`](versao.json) deste repositório:

```json
{
  "versao": "1.3.1",
  "url_download": "https://github.com/oliversoriano/HandHub-Releases/releases/download/..."
}
```

Se a versão publicada for maior que a instalada, o usuário é avisado e o novo executável é baixado pelo endereço em `url_download`.

Publicar uma atualização é só:

1. Gerar o novo `HandHub.exe` e anexá-lo a uma release.
2. Atualizar `versao` e `url_download` no `versao.json`.

## 📈 Histórico

O projeto está em uso e evolução constante: foram mais de **25 versões publicadas** entre junho e julho de 2026 (da 1.0.0 à 1.3.1), com melhorias feitas a partir do retorno do time de suporte.

## 🔒 Código-fonte

O código-fonte do HandHub é privado, por ser uma ferramenta de uso interno. Este repositório contém apenas os arquivos de distribuição.

## 👤 Autor

Desenvolvido por **[Oliver Soriano](https://github.com/oliversoriano)**.
