* * *

layout: default language: 'en' version: '4.0' title: 'Phalcon\Mvc\View\Engine\Php'

* * *

# Class **Phalcon\Mvc\View\Engine\Php**

*extends* abstract class [Phalcon\Mvc\View\Engine](/3.4/en/api/Phalcon_Mvc_View_Engine)

*implements* [Phalcon\Mvc\View\EngineInterface](/3.4/en/api/Phalcon_Mvc_View_EngineInterface), [Phalcon\Di\InjectionAwareInterface](/3.4/en/api/Phalcon_Di_InjectionAwareInterface), [Phalcon\Events\EventsAwareInterface](/3.4/en/api/Phalcon_Events_EventsAwareInterface)

<a href="https://github.com/phalcon/cphalcon/tree/v3.4.0/phalcon/mvc/view/engine/php.zep" class="btn btn-default btn-sm">源码在GitHub</a>

Adapter to use PHP itself as templating engine

## 方法

public **render** (*mixed* $path, *mixed* $params, [*mixed* $mustClean])

Renders a view using the template engine

public **__construct** ([Phalcon\Mvc\ViewBaseInterface](/3.4/en/api/Phalcon_Mvc_ViewBaseInterface) $view, [[Phalcon\DiInterface](/3.4/en/api/Phalcon_DiInterface) $dependencyInjector]) inherited from [Phalcon\Mvc\View\Engine](/3.4/en/api/Phalcon_Mvc_View_Engine)

Phalcon\Mvc\View\Engine constructor

public **getContent** () inherited from [Phalcon\Mvc\View\Engine](/3.4/en/api/Phalcon_Mvc_View_Engine)

Returns cached output on another view stage

public *string* **partial** (*string* $partialPath, [*array* $params]) inherited from [Phalcon\Mvc\View\Engine](/3.4/en/api/Phalcon_Mvc_View_Engine)

Renders a partial inside another view

public **getView** () inherited from [Phalcon\Mvc\View\Engine](/3.4/en/api/Phalcon_Mvc_View_Engine)

Returns the view component related to the adapter

public **setDI** ([Phalcon\DiInterface](/3.4/en/api/Phalcon_DiInterface) $dependencyInjector) inherited from [Phalcon\Di\Injectable](/3.4/en/api/Phalcon_Di_Injectable)

Sets the dependency injector

public **getDI** () inherited from [Phalcon\Di\Injectable](/3.4/en/api/Phalcon_Di_Injectable)

Returns the internal dependency injector

public **setEventsManager** ([Phalcon\Events\ManagerInterface](/3.4/en/api/Phalcon_Events_ManagerInterface) $eventsManager) inherited from [Phalcon\Di\Injectable](/3.4/en/api/Phalcon_Di_Injectable)

Sets the event manager

public **getEventsManager** () inherited from [Phalcon\Di\Injectable](/3.4/en/api/Phalcon_Di_Injectable)

返回内部事件管理器

public **__get** (*mixed* $propertyName) inherited from [Phalcon\Di\Injectable](/3.4/en/api/Phalcon_Di_Injectable)

Magic method __get