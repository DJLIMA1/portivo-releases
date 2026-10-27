# Portivo — releases

Este repositório só hospeda as versões publicadas do Portivo e as listas de atualização (appcasts) lidas pelos apps. O código-fonte não fica aqui.

- `appcast/macos.xml`: lista de versões do Mac (Sparkle 2).
- `appcast/windows.xml`: lista de versões do Windows (WinSparkle).

Cada pacote listado tem assinatura Ed25519 (`sparkle:edSignature`); os apps recusam qualquer pacote sem assinatura válida. Os instaladores ficam anexados às Releases deste repositório.
