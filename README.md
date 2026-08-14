# txt_files_for_a_workshop

from mistralai import Mistral

# Workshop: indsæt din API-nøgle mellem anførselstegnene nedenfor
# Opret nøgle på https://console.mistral.ai/
# VIGTIGT: Fjern nøglen igen, før du deler notebooken eller uploader til GitHub
api_key = 'INDSÆT DIN NØGLE HER'

if api_key == 'INDSÆT DIN NØGLE HER' or not api_key.strip():
    raise ValueError('Indsæt din Mistral API-nøgle i variablen api_key ovenfor')

# Vælg en model, din konto har adgang til (ofte 'mistral-small-latest' eller tilsvarende)
mistral_model = 'mistral-small-latest'

client = Mistral(api_key=api_key)
