# Annotations

---

- [Annotations](#annotations)
  - [Install from Scratch](#install-from-scratch)

<a name="install-from-scratch"></a>

## Install from Scratch

Execute this commands out of this project folder.

```bash
curl -s https://laravel.build/restaurants | bash
cd restaurants && ./vendor/bin/sail up -d
composer require binarytorch/larecipe
php artisan larecipe:install
composer require laravel/jetstream
php artisan jetstream:install livewire --teams
npm install && npm run dev
./vendor/bin/sail artisan migrate:fresh --seed
php artisan vendor:publish --tag=jetstream-views
```
