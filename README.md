# Amasty Mage 2.4.7-fix
After upgrade Magento to version 2.4.7 
you may encounter with broken wysiwig elements on the admin pages 
or some ui components stopped displaying.  

This bug is related to the latest Magento changes.
To see more information please visit:
- https://github.com/magento/magento2/pull/38537
- https://github.com/magento/magento2/pull/38623
- https://github.com/magento/magento2/issues/38622

If you are Amasty customer, you can fix this error by installing additional package from our private repository:

`composer require amasty/module-mage-2.4.7-fix`

But this case can be reproduced without our extensions.  
This is why we made this package public.
