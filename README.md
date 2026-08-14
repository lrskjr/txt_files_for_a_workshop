# txt_files_for_a_workshop

from mistralai import Mistral

api_key = 'INDSÆT DIN NØGLE HER'

if api_key == 'INDSÆT DIN NØGLE HER' or not api_key.strip():
    raise ValueError('Indsæt din Mistral API-nøgle i variablen api_key ovenfor')


mistral_model = 'mistral-small-latest'

client = Mistral(api_key=api_key)
