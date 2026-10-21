<div align="center">

<img src="assets/logo-tropical.png" alt="Tropical Multiloja" width="220">

# TropiBackup

**Sinergi | Software e Serviços de Gestão**

*Tropi Backup — distribuição oficial para Windows*

![Versão](https://img.shields.io/badge/vers%C3%A3o-0.4.9-0078D4)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4)
![.NET](https://img.shields.io/badge/.NET-10-512BD4)

### [⬇️ BAIXAR TROPIBACKUP V0.4.9 PARA WINDOWS](https://github.com/sinergitecnologia/tropibackup-updates/releases/download/v0.4.9/TropiBackup-Setup-0.4.9.exe)

**Versão estável atual: v0.4.9**

[Histórico de versões](https://github.com/sinergitecnologia/tropibackup-updates/releases) · [Código-fonte](https://github.com/sinergitecnologia/tropibackup)

</div>

---

## Distribuição oficial

Este repositório contém os instaladores e manifestos de atualização do **TropiBackup**, aplicativo Windows de backup e restauração de dados distribuído pela **Sinergi | Software e Serviços de Gestão**.

## Instalação

1. Baixe o instalador no link acima.
2. Execute como administrador em um computador Windows x64 compatível com .NET 10.
3. Siga as instruções do instalador.
4. Abra o TropiBackup e configure suas operações de backup.

O serviço Windows é identificado como `TropiBackupService`. Dados persistentes são mantidos em `C:\ProgramData\TropiBackup` e não devem ser apagados durante atualizações.

## Atualizações automáticas

O TropiBackup consulta o canal estável de atualizações através de:

`https://github.com/sinergitecnologia/tropibackup-updates/releases/latest/download/update-manifest.json`

Cada versão publicada contém:

| Arquivo | Finalidade |
|---|---|
| `TropiBackup-Setup-VERSAO.exe` | Instalador Windows |
| `update-manifest.json` | Metadados de atualização assinados digitalmente |

O aplicativo verifica a assinatura **ECDSA** do manifesto e confere o **SHA-256** e o tamanho do instalador antes de executá-lo. A atualização automática da versão 0.4.8 para a 0.4.9 foi validada operacionalmente.

## Segurança e publicação

- A chave privada de assinatura **não** é distribuída neste repositório.
- As versões publicadas não devem ter seus instaladores ou manifestos substituídos silenciosamente.
- A promoção de uma release para `latest` disponibiliza a atualização aos clientes do canal estável.
- Antes de atualizar, confirme que não há backups em execução.

## Documentação técnica

Consulte o [repositório do TropiBackup](https://github.com/sinergitecnologia/tropibackup) para arquitetura, instalação, documentação operacional e código-fonte.

---

<div align="center">

<img src="assets/logo-tropical.png" alt="Tropical Multiloja" width="220">

**Sinergi | Software e Serviços de Gestão**

*Tropi Backup — distribuição oficial para Windows*

</div>
