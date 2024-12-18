# 🛡️ **Approche des Protocoles TCP et IP**

---

## 📄 **Description**

Ce dépôt contient des ressources dédiées à l'analyse des protocoles **TCP/IP** avec **Wireshark** et **Packet Tracer**. Vous y trouverez des captures de paquets au format `.pcap`, des fichiers Packet Tracer au format `.pka`, un script pour automatiser certaines tâches et des fichiers texte pour comprendre les principales caractéristiques des protocoles TCP/IP.

Cet atelier est conçu pour vous aider à développer des compétences en inspection, diagnostic et simulation de trames réseau.

---

## 📖 **Qu'est-ce que TCP/IP ?**

**TCP/IP** (Transmission Control Protocol/Internet Protocol) est un ensemble de protocoles fondamentaux pour les communications sur Internet. Il permet de :

- **Garantir une transmission fiable des données**.
- **Acheminer les paquets à travers des réseaux interconnectés**.
- **Segmenter et réassembler les données**.
- **Identifier les appareils avec des adresses IP uniques**.

### 🔗 **Principaux Protocoles TCP/IP**

- **IP (Internet Protocol)** : Acheminement des paquets de données.
- **TCP (Transmission Control Protocol)** : Transmission fiable et en séquence.
- **UDP (User Datagram Protocol)** : Transmission rapide sans garantie de livraison.
- **ICMP (Internet Control Message Protocol)** : Diagnostic et messages d'erreur.

---

## 📂 **Contenu du Dépôt**

- **`documentation/`** : Guides et tutoriels d'analyse des protocoles TCP/IP.
  - `B1_Reseau_VIALETTE_CANDICE_Atelier02_pratique_TCP-IP.docx` : Document de référence pour l'atelier.

- **`captures/`** : Captures de paquets au format `.pcap` pour analyse avec Wireshark.
  - `20241213_ICMP_172.31.1.67_1.pcap` : Exemple de capture ICMP.
  - `Trame_avancée.txt` : Description d'une trame complexe.

- **`packet_tracer/`** : Fichiers Packet Tracer pour simulation au format `.pka`.
  - `simulation_tcp_ip_1.pka` : Scénario de simulation TCP/IP.

- **`scripts/`** : Scripts pour automatiser les tâches d'analyse.
  - `analyse_tcp_ip.sh` : Script d'analyse automatique des trames TCP/IP.

- **`textes/`** : Fichiers texte pour compléments d'informations.
  - `guide_tcp.txt` : Guide des protocoles TCP.

- **`README.md`** : Guide du dépôt.

---

## ⚙️ **Prérequis**

- **Cisco Packet Tracer** installé pour les simulations.
  - [Télécharger Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)

- Connaissances de base sur les protocoles réseau :
  - **ICMP**, **TCP**, **UDP**, **IP**.

---

## 🚀 **Mise en Œuvre**

### 1. **Cloner le Dépôt**

```bash
git clone https://github.com/votre_nom_utilisateur/tcp-ip-approche.git
cd tcp-ip-approche
```

### 2. **Parcourir la Documentation**

Consultez le dossier `documentation/` pour des guides d'analyse des protocoles TCP/IP.

### 3. **Ouvrir les Simulations Packet Tracer**

1. Lancez **Cisco Packet Tracer**.
2. Importez les fichiers `.pka` disponibles dans le dossier `packet_tracer/`.


## 💡 **Bonnes Pratiques**

- **Sauvegardez régulièrement vos configurations** pour éviter toute perte de données.
- **Utilisez des annotations** pour documenter vos topologies réseau.
- **Testez différents scénarios** pour comprendre le comportement des protocoles.



---

## 📚 **Ressources Utiles**
- [Tutoriels Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)
- [Présentation TCP/IP](https://www.gralon.net/articles/internet-et-webmaster/logiciel/article-le-protocole-tcp-ip---presentation-et-fonctionnement-1597.htm)
  
---

## 🌍 **Licence**

Ce projet est sous licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus d'informations.

---

### 🗓 **Date de Création**

Septembre 2024
