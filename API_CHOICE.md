# API Choice

- Étudiant : Di Renzo Julie
- API choisie : Frankfurter
- URL base : https://api.frankfurter.app
- Documentation officielle / README : https://frankfurter.dev
- Auth : None / API Key / OAuth
- Endpoints testés : 
  - GET /latest?from=EUR
  - GET /latest?from=EUR&to=USD
- Hypothèses de contrat (champs attendus, types, codes) : HTTP 200 pour une requête valide, réponses en JSON, attendus : base (texte), date (texte), rates (objet contenant des nombres)
- Limites / rate limiting connu : limité nous même
- Risques (instabilité, downtime, CORS, etc.) : peut être indispo ou lent
