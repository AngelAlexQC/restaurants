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
./vendor/bin/sail composer require binarytorch/larecipe
./vendor/bin/sail artisan larecipe:install
./vendor/bin/sail composer require laravel/jetstream
./vendor/bin/sail artisan jetstream:install livewire --teams
./vendor/bin/sail npm install && ./vendor/bin/sail npm run dev
./vendor/bin/sail artisan migrate:fresh --seed
./vendor/bin/sail artisan vendor:publish --tag=jetstream-views
```
