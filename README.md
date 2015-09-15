# docker-phpmyadmin

    docker build -t phpmyadmin .

    docker run --name="phpmyadmin" --env=["VIRTUAL_HOST=phpmyadmin.example.com"] --link=[mysql:mysql] -d phpmyadmin

