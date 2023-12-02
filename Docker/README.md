1. install docker dan setup docker
Lakukan instalasi docker dan setup docker diatas laptop atau pc
<img width="526" alt="image" src="https://github.com/nova34tkj4/Steradian/assets/26535997/46870e7c-3029-43ec-a68f-e34c05202b2a">

2. Deploy postgresql diatas docker dengan volume dedicated menggunakan docker compose
Lakukan deploy image postgresql(https://hub.docker.com/_/postgres) ke atas docker dengan volume persitance dengan terlebih dahulu lakukan create volume
<img width="959" alt="image" src="https://github.com/nova34tkj4/Steradian/assets/26535997/2b6325d1-2582-4ff5-a2f2-6c76fc2ae802">

<img width="887" alt="image" src="https://github.com/nova34tkj4/Steradian/assets/26535997/1729434c-7557-4e65-8b6d-01ddf19b4941">

<img width="698" alt="image" src="https://github.com/nova34tkj4/Steradian/assets/26535997/602c0a83-6f8a-4fb0-a961-3f6b78b66603">

3. Deploy apache php
Lakukan deploy image apache php (https://hub.docker.com/_/php) ke
atas docker dengan expose port 8080
<img width="960" alt="image" src="https://github.com/nova34tkj4/Steradian/assets/26535997/85407339-b547-4036-9ac3-3d42f2b799bf">

4. Deploy nginx
Lakukan deploy image nginx (https://hub.docker.com/_/nginx) ke atas
docker dengan expose port 80
<img width="959" alt="image" src="https://github.com/nova34tkj4/Steradian/assets/26535997/18b149e8-38cf-436c-b3b3-a4171c8efb1d">

5. deploy golang example
(https://docs.docker.com/language/golang/build-images/)

<img width="697" alt="image" src="https://github.com/nova34tkj4/Steradian/assets/26535997/d899efa0-c70f-4925-a16a-886c1dc4e444">

<img width="959" alt="image" src="https://github.com/nova34tkj4/Steradian/assets/26535997/fa6a3193-3cce-4918-bf45-fe4c6d7faddc">

6. menghubungkan apache php supaya bisa di akses lewat nginx
hubungkan apche php yang sudah di install supaya bisa di akses melalui
port 80 yang nginx
