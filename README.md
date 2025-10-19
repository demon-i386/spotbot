# Spotbot

**AVISO IMPORTANTE:**  
Este projeto contém uma automação que interage com o Spotify.  
Use **somente** para fins legítimos, de teste ou aprendizado, e sempre em conformidade com os Termos de Serviço do Spotify e da legislação aplicável.  
Automação usada para fraudar métricas, manipular contagens ou violar políticas pode resultar em banimento e sanções legais.

---

## 🧩 Configuração

A configuração é feita **diretamente no código**.  
Abra o arquivo principal (`spotbot.py`, `main.py`, etc.) e edite as seguintes variáveis no início do código:

```python
# --- CONFIGURAÇÃO (edite aqui) ---
API_KEY_CAPSOLVER = "API_KEY"        # Substitua por sua chave da API do Capsolver
USER_SPOTIFY = "artist name"         # Substitua pelo nome do artista alvo
# -----------------------------------
```
## ⚙️ Descrição

Spotbot é uma automação que realiza interações controladas no Spotify, incluindo:
Escutar/reproduzir faixas (para testes ou simulação controlada)
Adicionar músicas aos favoritos
Seguir artistas automaticamente
Suporte a múltiplas threads para paralelismo

### 🌐 Capsolver

Site: https://www.capsolver.com/pt

Uso: resolver reCAPTCHAs automaticamente quando necessário.
