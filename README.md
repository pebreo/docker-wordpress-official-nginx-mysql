
Wordpress + Nginx + MySQL
--------------------------


    dma ssh staging
    mkdir -p /root/wordpress/wp-content

    dc build
    dc up -d
    # wait a few moments for wordpress to start then you can go to the site