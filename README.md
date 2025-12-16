# POCO-X6-Pro-GameHub-Eden
Lista de compatibilidade para POCO X6 Pro 12/512 (Dimensity 8300 Ultra) com GameHub (PC/Steam) e Eden (Switch). Testes reais, configurações exatas(Nos vídeos), FPS médio e tweaks necessários. Vídeos dos testes no canal YouTube.

# GameHub & Eden Compatibility List

Lista mantida com testes reais no **POCO X6 Pro (512GB, Dimensity 8300 Ultra, Mali GPU)**.

## 📱 Especificações do dispositivo
- **SoC**: MediaTek Dimensity 8300 Ultra
- **GPU**: Mali-G615 MC6
- **RAM**: 12GB LPDDR5X
- **Armazenamento**: 512GB UFS 4.0
- **Emuladores testados**:
  - GameHub AnTuTu v5.3.5+
  - Eden v0.0.4+

## 🔑 Legenda de Status
- ✅ **Funciona bem** (~30+ FPS estável)
- ⚠️ **Jogável** (20-30 FPS, alguns stutters)
- ❌ **Não funciona** (crash/tela preta/baixo FPS)
- 🔸 **Não verificado** (relato de terceiros)

**Vídeos dos testes:** [POCO X6 Pro GameHub & Eden](https://youtube.com/@pocox6progamehubeden?si=1WjQlFzg6e3E7qlD)

**Última atualização:** 16/12/2025

---

## 💻 GameHub (PC/Steam)

| Jogo | Status | Configuração do Jogo | Configuração GameHub | Dependências | FPS Médio | Vídeo | Verificado | Nota |
|------|--------|---------------------|---------------------|--------------|-----------|-------|------------|-------|
| Resident Evil 4 UHD | ✅ | Tudo Low com texturas HD, 720p, 30 FPS | Proton9.0-x64-3, Parâmetros de Tradução: Desempenho, DXVK-1.7.2, VKD3D-2.12, Box64-0.37-b1 | ~30 FPS | [https://youtu.be/FXfVOSa7yK8?si=ijrhxxIoa6hlT0FO] | ✅ Sim | O mod Re4_Tweaks é obrigatório para não dar tela preta com audio. Pois, o RE4 UHD é imcompatível com telas com taxa de atualização maior, e o mod resolve isso.
| ABZÛ | ❌ | - | - | Base | - | - | ✅ | Não incia em nenhuma configuração nessa GPU |
|Clone Drone in the Danger Zone| ❌ | Fast, 720P|Proton10.0-ARM64-2, DXVK-1.10.3-async, vkd3d-2.12, Fex_20250910| Base |20-40|-------|✅|O Jogo tanto com Proton e Proton ARM64 é completamente instável. No menu e depois de acabar o level, fica entre 30-40 FPS. Durante a partida fica abaixo de 15 FPS|
---

## 🎮 Eden (Switch)

| Jogo | Status | Configuração | FPS Médio | Vídeo | Verificado | Nota |
|------|--------|--------------|-----------|-------|------------|--------|
| (em breve) | | | | | |

---

## 📝 Como contribuir
1. Testou outro jogo? Abre uma **Issue** com: nome do jogo, status, configs usadas, FPS aproximado
2. Tem vídeo? Compartilha o link
3. Encontrou correção? Manda **Pull Request**

**⚠️ Aviso:** Resultados específicos do POCO X6 Pro (Dimensity 8300). Pode variar em outros aparelhos.
---
