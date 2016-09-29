Основные консольные команды magento2:
bin/magento --list    // выводит список всех команд
Чистка кеша:
bin/magento cache:clean 
rm -rf cache && rm -rf log && rm -rf page_cache && rm -rf view_preprocessed

Создание конечных браузерных файлов:
bin/magento setup:static-content:deploy

Обновление модулей:
bin/magento setup:upgrade

Перестройка расчётных таблиц:
bin/magento indexer:reindex

Создание учётной записи админа:
bin/magento admin:user:create --admin-user="Weblips" --admin-password="ABC12345d" --admin-email="admin@test.com" --admin-firstname="Web" --admin-lastname="Lips"
