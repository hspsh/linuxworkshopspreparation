# linuxworkshopspreparation
Trochę po ch skrypt w ansiblu, ale ogarnia stworzenie wielu userów, ustawia im hasło, wrzuca materiały do ćwiczeń i ich /home oraz ustawia sshd by przyjmował logowanie hasłem.

Ustaw w inventory hostname na swoją maszynę.

Postaw venva pythonowego. Potem pip install ansible

Odpal ansible-playbook -i inventory.yaml playbook.yaml
