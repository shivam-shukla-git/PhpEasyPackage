# PhpEasyPackage
Make your code easy by adding our PhpEasyPackage. It will reduce code bloats from the your PHP code. common things are described as a function to implement reuse-ability.


We are still in the development phase so most of the features are not listed here but don't worry I will add them soon and expand the pacakage by adding new features to use. If you have any suggestions please contact at shivamshukla7187@gmail.com.

###### find to eliminate the use of strpos
###### can trigger any php error
###### can return any status header

### Getting Started
Clone the module locally:
```
git clone https://github.com/shivam-shukla-git/PhpEasyPackage.git
```

**How to use in the file**


1. Create a instance of the PhpEasyPackage Class to use.

`use PhpEasyPackage\classes\PhpCommonFunctions as php;`

You can use any keyword for class instance like i use the keyword php. Like: php, example, EasyPackage or anything else.

2. Require `PhpEasyPackage/autoload.php` file from clone directory folder.

`require "PhpEasyPackage/autoload.php";`

You can use the package features now.

You can verify by running anything like this

`PhpCommonFunctions::isEmail("shivamshukla7187@gmail.com")` It return boolen response depend upon expression result.

I will Update the readme file soon to explain all the features.