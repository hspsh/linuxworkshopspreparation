# linuxworkshopspreparation
Trochę skrypt po ch w ansiblu, ale ogarnia stworzenie wielu userów, ustawia im hasło, wrzuca materiały do ćwiczeń i ich /home oraz ustawia sshd by przyjmował logowanie hasłem.

Ustaw w inventory.yml hostname na swoją maszynę.

Postaw venva pythonowego. Potem pip install ansible

W pliku roles/add-users/tasks/main.yml w tasku: "Ansible copy directory to the remote server"
znajdź linijkę: src: "/Users/proko/Desktop/linux-hs"
Podmień zawartość na ścieżkę do materiałów, które mają być wgrane do katalogu każdego usera.

Odpal ansible-playbook -i inventory.yml playbook.yml
