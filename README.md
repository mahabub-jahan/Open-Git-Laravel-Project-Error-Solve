# Download GitHub Laravel Project Errror Solve 
- Error Nmae: "
  [ErrorException] 
  ZipArchive::extractTo(E:\Google Drive\Onedrive\Programming\Web Development\Laravel\Laracast\Laravel 5.4    Scratch\Laracast_Blog/vendor/composer/f9ee0410/sebastianber gmann-phpunit-mock-objects 2f789b5\tests\Generator/namespaced_class_implementing_interface_call_parent_constructor.phpt): failed to open stream: No such file or directory
install [--prefer-source] [--prefer-dist] [--dry-run] [--dev] [--no-dev] [--no-custom-installers] [--no-autoloader] [--no-scripts] [--no-progress] [--no-suggest] [-v|vv|vvv|--verbose] [-o|--optimize-autoloader] [-a|--classmap-authoritative] [--apcu-autoloader] [--ignore-platform-reqs] [--] [<packages>]...
 "
  ## Solve Error
  - Write this command
  - composer update
  - If it gives that error then 
  - composer update --prefer-source (It gives a successful message, If not try another like composer update --prefer-dist)
  - php artisan key:generate
  - php artisan migrate
  - php artisan migrate
  
