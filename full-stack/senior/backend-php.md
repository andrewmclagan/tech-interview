Below are PHP / Laravel senior level full stack developer Q&As.

-------------------------

### 1. Writing clean and testable code

*Rewrite the class below to be more testable and clean*

```php
class User
{
    public static function getUsersByAge(int $age): ?Collection
    {
        $users = DB::table('users')
            ->where('age', $age)
            ->get();

        if ($users->count() > 0) {
            return $users;
        }

        return null;
    }
}
```

```php
// paste your code here
```

-------------------------

### 2. Redis

*What are the advantages of using Redis as the cache and queue drivers over the php array driver?*

-------------------------


### 3. Eloquent and the database

*Explain the differences between eager loading and lazy loading in eloquent models.*

-------------------------

### 4. Modern PHP

*What is your favourite language feature introduced in PHP 7.4? Why do you like it? What advantages does it offer?*

