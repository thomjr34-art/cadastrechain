# CadastrChain Cameroun 🇨🇲⛓

> Système décentralisé de gestion des titres fonciers basé sur
> Hyperledger Fabric + Ethereum + IPFS pour le Cameroun.

## Stack Technique
- **Blockchain privée** : Hyperledger Fabric 2.5
- **Ancrage public**    : Ethereum (Polygon L2)
- **Stockage docs**     : IPFS (nœuds locaux Cameroun)
- **Smart Contracts**   : Chaincode Go + Solidity
- **API Backend**       : Node.js + Express + Fabric SDK
- **App Mobile**        : React Native (iOS + Android + USSD)
- **Dashboard Admin**   : Next.js + TypeScript

## Lancement rapide
```bash
# 1. Cloner et initialiser
git clone https://github.com/mindcaf/cadastrechain
cd cadastrechain && npm run setup

# 2. Démarrer le réseau Fabric (local)
cd blockchain/fabric && ./scripts/start-network.sh

# 3. Déployer le chaincode
./scripts/deploy-chaincode.sh titrefoncier

# 4. Démarrer l'API
cd ../../backend && npm run dev

# 5. Démarrer le dashboard
cd ../dashboard && npm run dev
```

## Documentation
- [Architecture technique](docs/architecture/README.md)
- [Guide déploiement](docs/deployment/README.md)
- [API Reference](docs/api/README.md)
- [Cadre légal camerounais](docs/legal/README.md)

## Textes législatifs de référence
- Ordonnance n° 74-1 du 6 juillet 1974
- Décret n° 76-165 du 27 avril 1976
- Décret n° 2005/481 du 16 décembre 2005
# cadastrechain
