<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Portfolio d'Eloham Caron</title>
    <!-- Importation des polices Google Fonts -->
    <link href="https://fonts.googleapis.com/css?family=Ubuntu&display=swap" rel="stylesheet">
    <!-- Importation de Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Importation de la bibliothèque AOS pour les animations -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css">
    <!-- Votre fichier CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Barre de navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">Eloham Caron</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" 
                aria-controls="navbarNav" aria-expanded="false" aria-label="Basculer la navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">À propos</a></li>
                    <li class="nav-item"><a class="nav-link" href="#skills">Compétences</a></li>
                    <li class="nav-item"><a class="nav-link" href="#experience">Expériences</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projets</a></li>
                    <li class="nav-item"><a class="nav-link" href="#certifications">Certifications</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Section principale -->
    <div class="container-fluid p-0">

        <!-- Section de présentation -->
        <section id="home" class="d-flex align-items-center">
            <div class="container text-center" data-aos="fade-down">
                <img src="img/eloham.png" alt="Photo d'Eloham Caron" class="profile-photo rounded-circle mb-4">
                <h1 class="display-4">Eloham Caron</h1>
                <p class="lead">Administrateur Réseaux & Analyste en Sécurité Informatique</p>
            </div>
        </section>

        <!-- Section À propos -->
        <section id="about" class="py-5">
            <div class="container" data-aos="fade-up">
                <h2 class="mb-4">À propos de moi</h2>
                <p>Je suis un Administrateur Réseaux et Analyste en Sécurité Informatique passionné, classé parmi les 4% meilleurs mondiaux sur TryHackMe. Je suis spécialisé dans l'identification et la correction des vulnérabilités pour protéger les systèmes et les réseaux.</p>
                <h3>Mes intérêts :</h3>
                <ul>
                    <li>Sécurité des réseaux</li>
                    <li>Évaluation des vulnérabilités</li>
                    <li>Tests de pénétration</li>
                    <li>Hacking éthique</li>
                    <li>Formation en cybersécurité</li>
                </ul>
                <h3>Je suis ouvert à :</h3>
                <ul>
                    <li>Toute collaboration</li>
                    <li>Projets de tests de pénétration (développement ou recherche)</li>
                    <li>Stages de recherche</li>
                </ul>
            </div>
        </section>

        <!-- Section Compétences -->
        <section id="skills" class="py-5 bg-light">
            <div class="container" data-aos="fade-up">
                <h2 class="mb-4">Compétences</h2>
                <div class="row">
                    <!-- Langues -->
                    <div class="col-md-6">
                        <h3>Langues</h3>
                        <ul>
                            <li>Français (natif)</li>
                            <li>Anglais (B2)</li>
                        </ul>
                    </div>
                    <!-- Langages de programmation -->
                    <div class="col-md-6">
                        <h3>Langages de programmation</h3>
                        <ul>
                            <li>Python</li>
                            <li>SQL</li>
                            <li>Shell Script</li>
                            <li>PowerShell</li>
                            <li>Java</li>
                            <li>HTML</li>
                        </ul>
                    </div>
                    <!-- Outils de sécurité -->
                    <div class="col-md-6">
                        <h3>Outils de sécurité</h3>
                        <ul>
                            <li>Nmap</li>
                            <li>Wireshark</li>
                            <li>Metasploit</li>
                            <li>Hydra</li>
                            <li>Gobuster</li>
                            <li>Exploit-DB</li>
                            <li>Netmiko</li>
                            <li>Ettercap</li>
                            <li>Shodan</li>
                            <li>OpenVAS</li>
                            <li>Burp Suite</li>
                        </ul>
                    </div>
                    <!-- Administration réseau -->
                    <div class="col-md-6">
                        <h3>Administration réseau</h3>
                        <ul>
                            <li>Cisco</li>
                            <li>Kali Linux</li>
                        </ul>
                    </div>
                    <!-- Systèmes d'exploitation -->
                    <div class="col-md-6">
                        <h3>Systèmes d'exploitation</h3>
                        <ul>
                            <li>Ubuntu</li>
                            <li>Kali Linux</li>
                            <li>Arch Linux</li>
                        </ul>
                    </div>
                    <!-- Bases de données -->
                    <div class="col-md-6">
                        <h3>Bases de données</h3>
                        <ul>
                            <li>MySQL</li>
                            <li>PostgreSQL</li>
                        </ul>
                    </div>
                    <!-- Outils et technologies -->
                    <div class="col-md-6">
                        <h3>Outils et technologies</h3>
                        <ul>
                            <li>AWS</li>
                            <li>Azure</li>
                            <li>Git</li>
                            <li>VMware</li>
                            <li>VirtualBox</li>
                        </ul>
                    </div>
                    <!-- Environnements de développement -->
                    <div class="col-md-6">
                        <h3>Environnements de développement</h3>
                        <ul>
                            <li>PyCharm</li>
                            <li>Visual Studio Code</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section Expériences -->
        <section id="experience" class="py-5">
            <div class="container" data-aos="fade-up">
                <h2 class="mb-4">Expériences Professionnelles</h2>
                <div class="timeline">
                    <div class="timeline-item" data-aos="fade-right">
                        <h3>Pentesteur chez l'Éducation Nationale</h3>
                        <span>2023 - Présent</span>
                        <p>Réalisation de tests de pénétration pour identifier et corriger les vulnérabilités dans les établissements scolaires de la région Auvergne-Rhône-Alpes.</p>
                    </div>
                    <div class="timeline-item" data-aos="fade-left">
                        <h3>Informaticien chez Connexion Partenaire Boulanger Les Vans</h3>
                        <span>2021 - 2023</span>
                        <p>CDD durant les deux derniers étés avec un total de 12 semaines de stage. Support technique, maintenance du parc informatique et assistance aux utilisateurs.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section Projets -->
        <section id="projects" class="py-5 bg-light">
            <div class="container" data-aos="fade-up">
                <h2 class="mb-4">Projets</h2>
                <div class="row">
                    <!-- Projet 1 -->
                    <div class="col-md-6 mb-4" data-aos="zoom-in">
                        <div class="card">
                            <div class="card-body">
                                <h3 class="card-title">Sécurité Informatique Auvergne-Rhône-Alpes</h3>
                                <p class="card-text">Création du groupe LinkedIn "Sécurité Informatique Auvergne-Rhône-Alpes" pour regrouper les professionnels et les passionnés de cybersécurité dans la région. Détection et gestion de failles de sécurité dans les établissements publics scolaires de la région.</p>
                            </div>
                        </div>
                    </div>
                    <!-- Projet 2 -->
                    <div class="col-md-6 mb-4" data-aos="zoom-in">
                        <div class="card">
                            <div class="card-body">
                                <h3 class="card-title">CTF TryHackMe</h3>
                                <p class="card-text">Participation à plusieurs Capture The Flag (CTF) sur la plateforme TryHackMe, notamment les challenges avancés comme "Mr. Robot". Réalisation régulière de défis pour améliorer les compétences en cybersécurité.</p>
                            </div>
                        </div>
                    </div>
                    <!-- Projet 3 -->
                    <div class="col-md-6 mb-4" data-aos="zoom-in">
                        <div class="card">
                            <div class="card-body">
                                <h3 class="card-title">Réseaux Virtuels sur Cisco Packet Tracer</h3>
                                <p class="card-text">Création et configuration de réseaux virtuels sur Cisco Packet Tracer. Mise en place de réseaux complets avec routage, commutation et sécurité pour simuler des environnements réels et tester des configurations réseau.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section Certifications -->
        <section id="certifications" class="py-5">
            <div class="container" data-aos="fade-up">
                <h2 class="mb-4">Certifications</h2>

                <!-- Bloc Réseaux -->
                <h3 class="mb-4">Réseaux</h3>
                <div class="row">
                    <!-- Certification CCNA -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-cisco.png" alt="Logo Cisco" class="mb-3" width="100">
                                <h4 class="card-title">CCNA: Introduction to Networks</h4>
                                <p><strong>Émetteur :</strong> Cisco</p>
                                <p><strong>Date de délivrance :</strong> Janvier 2023</p>
                                <a href="certif/ccna_introduction_networks.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Objectif IPv6 -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-institut-mines-telecom.png" alt="Logo Institut Mines-Télécom" class="mb-3" width="100">
                                <h4 class="card-title">Objectif IPv6</h4>
                                <p><strong>Émetteur :</strong> Institut Mines-Télécom</p>
                                <p><strong>Date de délivrance :</strong> Juillet 2023</p>
                                <a href="certif/objectif_ipv6.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Wireshark -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-wireshark.png" alt="Logo Wireshark" class="mb-3" width="100">
                                <h4 class="card-title">Competent with Wireshark & Packet Analysis</h4>
                                <p><strong>Émetteur :</strong> Wireshark Foundation</p>
                                <p><strong>Date de délivrance :</strong> Mars 2023</p>
                                <a href="certif/wireshark_packet_analysis.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Réseaux d'accès optiques FTTH -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-institut-mines-telecom.png" alt="Logo Institut Mines-Télécom" class="mb-3" width="100">
                                <h4 class="card-title">Réseaux d'accès optiques FTTH</h4>
                                <p><strong>Émetteur :</strong> Institut Mines-Télécom</p>
                                <p><strong>Date de délivrance :</strong> (Date non spécifiée)</p>
                                <a href="certif/reseaux_acces_optiques_ftth.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Bloc Développement -->
                <h3 class="mb-4">Développement</h3>
                <div class="row">
                    <!-- Certification Python Essentials 1 -->
                    <div class="col-md-6 mb-4" data-aos="flip-right">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-cisco.png" alt="Logo Cisco" class="mb-3" width="100">
                                <h4 class="card-title">Python Essentials 1</h4>
                                <p><strong>Émetteur :</strong> Cisco</p>
                                <p><strong>Date de délivrance :</strong> Octobre 2022</p>
                                <a href="certif/python_essentials_1.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Python Essentials 2 -->
                    <div class="col-md-6 mb-4" data-aos="flip-right">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-cisco.png" alt="Logo Cisco" class="mb-3" width="100">
                                <h4 class="card-title">Python Essentials 2</h4>
                                <p><strong>Émetteur :</strong> Cisco</p>
                                <p><strong>Date de délivrance :</strong> Août 2023</p>
                                <a href="certif/python_essentials_2.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Python Fondamentaux -->
                    <div class="col-md-6 mb-4" data-aos="flip-right">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-universite-cote-azur.png" alt="Logo Université Côte d’Azur" class="mb-3" width="100">
                                <h4 class="card-title">Python : Des Fondamentaux aux Concepts Avancés du Langage</h4>
                                <p><strong>Émetteur :</strong> Université Côte d’Azur</p>
                                <p><strong>Date de délivrance :</strong> Août 2023</p>
                                <a href="certif/python_fundamentals.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification DevNet Associate -->
                    <div class="col-md-6 mb-4" data-aos="flip-right">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-cisco.png" alt="Logo Cisco" class="mb-3" width="100">
                                <h4 class="card-title">DevNet Associate</h4>
                                <p><strong>Émetteur :</strong> Cisco</p>
                                <p><strong>Date de délivrance :</strong> Décembre 2022</p>
                                <a href="certif/devnet_associate.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Bash Scripting Basics -->
                    <div class="col-md-6 mb-4" data-aos="flip-right">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-cybrary.png" alt="Logo Cybrary" class="mb-3" width="100">
                                <h4 class="card-title">Bash Scripting Basics</h4>
                                <p><strong>Émetteur :</strong> Cybrary</p>
                                <p><strong>Date de délivrance :</strong> Février 2023</p>
                                <a href="certif/bash_scripting_basics.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Bloc Cybersécurité -->
                <h3 class="mb-4">Cybersécurité</h3>
                <div class="row">
                    <!-- Certification CompTIA CySA+ -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-comptia.png" alt="Logo CompTIA" class="mb-3" width="100">
                                <h4 class="card-title">CompTIA CySA+ (CS0-003)</h4>
                                <p><strong>Émetteur :</strong> CompTIA</p>
                                <p><strong>Date de délivrance :</strong> Septembre 2024</p>
                                <a href="certif/cysa.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Jr Penetration Tester -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-tryhackme.png" alt="Logo TryHackMe" class="mb-3" width="100">
                                <h4 class="card-title">Jr Penetration Tester</h4>
                                <p><strong>Émetteur :</strong> TryHackMe</p>
                                <p><strong>Date de délivrance :</strong> Mars 2023</p>
                                <a href="certif/jr_penetration_tester.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Advent of Cyber 4 -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-tryhackme.png" alt="Logo TryHackMe" class="mb-3" width="100">
                                <h4 class="card-title">Advent of Cyber 4</h4>
                                <p><strong>Émetteur :</strong> TryHackMe</p>
                                <p><strong>Date de délivrance :</strong> Décembre 2022</p>
                                <a href="certif/advent_of_cyber_4.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Advent of Cyber 2023 -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-tryhackme.png" alt="Logo TryHackMe" class="mb-3" width="100">
                                <h4 class="card-title">Advent of Cyber 2023</h4>
                                <p><strong>Émetteur :</strong> TryHackMe</p>
                                <p><strong>Date de délivrance :</strong> Décembre 2023</p>
                                <a href="certif/advent_of_cyber_2023.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Cybersecurity Essentials -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-cisco.png" alt="Logo Cisco" class="mb-3" width="100">
                                <h4 class="card-title">Cybersecurity Essentials</h4>
                                <p><strong>Émetteur :</strong> Cisco</p>
                                <p><strong>Date de délivrance :</strong> Avril 2023</p>
                                <a href="certif/cybersecurity_essentials.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Metasploit -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-tryhackme.png" alt="Logo TryHackMe" class="mb-3" width="100">
                                <h4 class="card-title">Metasploit</h4>
                                <p><strong>Émetteur :</strong> TryHackMe</p>
                                <p><strong>Date de délivrance :</strong> Février 2023</p>
                                <a href="certif/metasploit.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification SC-200 Microsoft Sentinel -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-microsoft.png" alt="Logo Microsoft" class="mb-3" width="100">
                                <h4 class="card-title">SC-200 : Configurer votre environnement Microsoft Sentinel</h4>
                                <p><strong>Émetteur :</strong> Microsoft</p>
                                <p><strong>Date de délivrance :</strong> Avril 2023</p>
                                <a href="certif/sc200_microsoft_sentinel.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification SecNumAcadémie -->
                    <div class="col-md-6 mb-4" data-aos="flip-left">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-anssi.png" alt="Logo ANSSI" class="mb-3" width="100">
                                <h4 class="card-title">SecNumAcadémie</h4>
                                <p><strong>Émetteur :</strong> ANSSI</p>
                                <p><strong>Date de délivrance :</strong> Mai 2023</p>
                                <a href="certif/secnumacademie.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Bloc Autres -->
                <h3 class="mb-4">Autres</h3>
                <div class="row">
                    <!-- Certification English for IT 1 -->
                    <div class="col-md-6 mb-4" data-aos="flip-right">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-cisco.png" alt="Logo Cisco" class="mb-3" width="100">
                                <h4 class="card-title">English for IT 1</h4>
                                <p><strong>Émetteur :</strong> Cisco</p>
                                <p><strong>Date de délivrance :</strong> Avril 2024</p>
                                <a href="certif/english_for_it_1.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Unlock Your English 2 -->
                    <div class="col-md-6 mb-4" data-aos="flip-right">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-institut-mines-telecom.png" alt="Logo Institut Mines-Télécom" class="mb-3" width="100">
                                <h4 class="card-title">Unlock Your English 2</h4>
                                <p><strong>Émetteur :</strong> Institut Mines-Télécom</p>
                                <p><strong>Date de délivrance :</strong> Septembre 2023</p>
                                <a href="certif/unlock_your_english_2.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Communication Orale -->
                    <div class="col-md-6 mb-4" data-aos="flip-right">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-article1.png" alt="Logo Article 1 - JOBREADY" class="mb-3" width="100">
                                <h4 class="card-title">Communication Orale</h4>
                                <p><strong>Émetteur :</strong> Article 1 - JOBREADY</p>
                                <p><strong>Date de délivrance :</strong> Mai 2021</p>
                                <a href="certif/communication_orale.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                    <!-- Certification Définissez la politique de sécurité -->
                    <div class="col-md-6 mb-4" data-aos="flip-right">
                        <div class="card h-100">
                            <div class="card-body">
                                <img src="img/logo-openclassrooms.png" alt="Logo OpenClassrooms" class="mb-3" width="100">
                                <h4 class="card-title">Définissez la politique de sécurité de votre entreprise</h4>
                                <p><strong>Émetteur :</strong> OpenClassrooms</p>
                                <p><strong>Date de délivrance :</strong> Avril 2021</p>
                                <a href="certif/openclassrooms_politique_securite.pdf" target="_blank" class="btn btn-primary">Voir le certificat</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section Contact -->
        <section id="contact" class="py-5 bg-light">
            <div class="container" data-aos="fade-up">
                <h2 class="mb-4">Contact</h2>
                <p>N'hésitez pas à me contacter pour toute collaboration ou opportunité.</p>
                <ul class="list-unstyled">
                    <li><strong>Email :</strong> <a href="mailto:eloham.caron@example.com">eloham.caron@example.com</a></li>
                    <li><strong>Téléphone :</strong> 06 00 00 00 00</li>
                    <li><strong>LinkedIn :</strong> <a href="https://www.linkedin.com/in/eloham-caron" target="_blank">Eloham Caron</a></li>
                    <li><strong>GitHub :</strong> <a href="https://github.com/elohamcaron" target="_blank">elohamcaron</a></li>
                </ul>
            </div>
        </section>

    </div>

    <!-- Pied de page -->
    <footer class="text-white text-center py-3">
        <p>&copy; 2023 Eloham Caron</p>
    </footer>

    <!-- Scripts JavaScript -->
    <!-- jQuery, Popper.js, Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <!-- AOS Library -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
    <script>
        // Initialisation de AOS
        AOS.init({
            duration: 1000,
            once: true,
        });
    </script>
</body>
</html>
