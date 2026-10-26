# catalogo-norme
Catalogo delle norme sulla protezione contro i fulmini (serie CEI EN IEC 62305) che l'app Ceraunia scarica all'avvio.
`norme.json` è firmato (Ed25519): la firma è in `norme.json.sig` e l'app accetta il catalogo solo se la firma è valida.
Non modificare i file a mano (anche un solo spazio invalida la firma): si pubblicano con `npm run norme:pubblica` dal repository dell'app.
