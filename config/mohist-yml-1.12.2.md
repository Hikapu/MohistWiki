### Mohist.yml

Путь к файлу `*/mohist-config/mohist.yml`

* `entity-tick-limit: 300`

* `hidejoinmodslist: false`  
  #: Скрыть список модов игрока

* `world`  
  #: Настройки связанные с миром
  - `directory_in_client: true`  
    #: Установите клиент на путь мирового хранилища
  - `stopserversaveworlds: false`  
    #: Не сохраняйте все миры, когда сервер выключен
  - `dimensionsNotLoaded: []`  
    #: Идентификаторы измерений в этом списке не будут загружены сервером

* `mohist`
  - `use_custom_java8: false`  
    #: После установки значения "true" вы можете использовать настроенную версию JAVA8
  - `check_update: true`  
    #: Обнаружение обновления версии Мохист
  - `server-type: FML`  
    #: Установите значок, отображаемый в правом нижнем углу клиентского MOTD, который может быть установлен в `FML` `BUKKIT` `VANILLA`
  - `lang: xx_XX`  
    #: The language of the console and internal prompts, the system language is used by default
  - `console_name: Server`  
    #: The prefix name displayed when sending information using the console
  - `CloseChatInConsole: false`  
    #: After opening, all the speeches of the player on the server will not be displayed in the console, but will still be recorded in the log
  - `check_libraries: true`  
    #: Check the library required for operation, if it does not exist, it will be downloaded automatically
  - `support_nocmd: false`  
    #: Some people who use panel servers need to enable this setting
  - `disable_mods_blacklist: false`  
    #: Turn off mods blacklist detection, most of them are incompatible or mods that have been implemented inside mohist
  - `disable_plugins_blacklist: false`  
    #: Turn off plugins blacklist detection, most of them are incompatible or plugins that have been implemented inside mohist
  - `check_update_auto_download: false`  
    #: Automatically download when new version is detected
  - `realtimeticking: false`  
    #: realtime？ This feature comes from SpongeForge
  - `watchdog_mohist: false`  
    #: Mohist's watchdog
  - `watchdog_spigot: true`  
    #: Spigot'swatchdog
  - `showlogo: true`  
    #: The character LOGO you will see when running Mohist
