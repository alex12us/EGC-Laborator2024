
                                              Tema _01


   Open GL (Open Graphics Library) este un API și nu un limbaj de programare și este folosit pentru a genera scene 2D sau 3D și pentru a desena obiecte pe ecran.
Open GL este folosit în limbajele de programare Java,C#,C++,C și Phyton.
    Web GL (Web Graphics Library) este un API folosit de Java Script pentru a genera grafici intereactive 2D sau 3D pentru aplicații web.
Vulkan este un derivat API al Open GL pentru aplicații de generație nouă,grafice 3D și calculul pe GPU-uri(Graphics Processing Unit) moderne.
     Avantajele OpenGL
         -este independentă de platformă (cross-platform) deoarece poate fi utilzat în diverse sisteme de operare(Windows,Linux,iOS,Android)
         -dezvoltatorii pot crea aplicații să funcționeze pe multiple dispozitive fără prea multe modificări
         -OpenGPL este flexibil astfel încât oferă funcții de nivel înalt și funcții de nivel scăzut pentru a ajusta grafica în mod personalizat și optimizat
     Dezavantajele OpenGL
           -evoluție lentă în privința adaptării la noile tehnologii și noi funcționalități
           -se comit erori când o gestionare manuală a resurselor a multor aspecte ale redării grafice nu este făcută cum trebuie
           -necesită cunoașterea pipeline-ului grafic și a programării shaderelor pentru a face funcțională
     Avantajele WebGL
         --oferă un suport larg pentru mariile companii de tehnologie și o documentație bogată în domeniul educațional
         --accelerază GPU pentru a face graficele să fie mai spectaculoase
         --este open source ,deoarece este gratuit și beneficiarii sunt comunitățile largi de dezvoltatori care au contribuit la îmbunătățire și extinderea sa.
         --se integrează ușor cu alte tehnologii web ceea ce îi permite dezvoltatorilor să facă aplicații mai dinamice și mai intereactive în browser.
     Dezavantajele WebGL
         --este dependentă de JavaScript
         --este vunerabilă la anumite atacuri cibernetice(exploatările prin shader).Deci securitatea este o prioritate pentru a dezvolta aplicații WebGL
          --este greu de învățat pentru cei care nu au experiență anterioară cu grafica 3D

    Avantajele Vulkan
          --Oferă perfomanță ridicată pentr că controlează GPU-ul mult mai bine și reduce utilizarea CPU-ului
          --Vulkan API permite dezvoltatorilor să gestioneze mult mai bine resursele hardware,oferind control detaliat
     Dezavantajele Vulkan
             --necesită cunoștiințe mai avansate ,deoarece Vulkan API este mai complexă decât OpenGL și WebGL
             --este greu de învățat pe termen scurt,dar ușor pe termen lung
              --adopția este limitată pentru că dezvoltatorii folosesc API-uri mult mai familarizate,mai ușor de înțeles

       Modelul automat cu stări finite în OpenGL este folosit pentru a gestiona diferite stări și tranziții ale pipeline-ului grafice în timpul proceselui de randare a graficii 3D.
  Stările sunt folosite pentru a modela obiectele desenate 3D,de exemplu se verifică starea iluminării dacă este activată sau dezactivată.
          Etapele unui model automat cu stări finite sunt:Vertex Processing,Primitive Assembly(Construirea primitivelor din vârfuri),Rasterizer,Fragment Processor,Output Merging.
     Aceste etape a graficii pipeline duc la crearea unei imagini finale ce va fi afișată pe ecran.
         Procesul de randare al scenei 3D este afectat de către biblioteca grafică prin controlul fluxului de execuție,
prin gestionarea stărilor și tranzițiilor ce duc la optimizarea perfomanței. Procesul de randare al scenei 3D mai poate fi afectat de gestionarea resurselor grafice precum texturile și buffer-ele care îmbunătățește 
grafica 3D.
     
         În concluzie,modelul automat cu stări finite are rolul de a asigura randări corecte și de a gestiona grafica pipeline mai eficient pentru scena 3D.
