## commands
php artisan make:migration create_articles_table --create=articles

php artisan make:seeder ArticlesTableSeeder

php artisan make:factory ArticleFactory
php artisan make:model Article
php artisan migrate
php artisan migrate:fresh --seed
php artisan db:seed
php artisan make:controller ArticleController --resource

php artisan make:resource ArticleResource

## Notes
<!-- use Illuminate\Http\Resources\Json\JsonResource -->
You can also use withoutRapping method on resource
