# linuxworkshopspreparation
Trochę skrypt po ch w ansiblu, ale ogarnia stworzenie wielu userów, ustawia im hasło, wrzuca materiały do ćwiczeń i ich /home oraz ustawia sshd by przyjmował logowanie hasłem.

Ustaw w inventory hostname na swoją maszynę.

Postaw venva pythonowego. Potem pip install ansible

W pliku roles/add-userts/tasks/main.yaml znajdź task: "Ansible copy directory to the remote server"
Podmień tam ścieżkę do materiałów, które mają być wgrane do katalogu każdego usera.

Odpal ansible-playbook -i inventory.yaml playbook.yaml
