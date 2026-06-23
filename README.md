# 🍦 Fanmilk Côte d'Ivoire — Vendor Bot WhatsApp

Bot WhatsApp pour la collecte quotidienne des déclarations vendors CI.

## Stack
- Flask (Python)
- WhatsApp Cloud API
- Google Sheets API
- Render (hébergement)

## Dépôts CI configurés
1. ABIDJAN NORD
2. ABIDJAN SUD
3. ABIDJAN EST
4. ABIDJAN OUEST
5. BOUAKE
6. YAMOUSSOUKRO
7. SAN-PEDRO
8. DALOA

## Variables d'environnement (Render)
| Variable | Description |
|---|---|
| `WHATSAPP_TOKEN` | Token WhatsApp Cloud API |
| `WHATSAPP_PHONE_ID` | ID du numéro WhatsApp CI |
| `WHATSAPP_VERIFY_TOKEN` | Token de vérification webhook |
| `GOOGLE_SHEET_ID` | ID du Google Sheet CI |
| `GOOGLE_SHEET_TAB` | Nom de l'onglet (Reponses Vendors) |
| `GOOGLE_CREDENTIALS_JSON` | Credentials service account Google |

## Déploiement sur Render
1. Créer un nouveau Web Service sur render.com
2. Importer ce repo
3. Ajouter les variables d'environnement
4. Déployer

## Dashboard
→ https://fanmilk-ci-dashboard.vercel.app
