Запуск командой: iex -S mix

Приложение при запуске инициализирует GenServer и следит за ним через SuperVisor.

Доступные действия:

1) KV.Registry.create(KV.Registry,[текст]) // занесение в карту

2) KV.Registry.lookup(KV.Registry,[текст]) // проверка на нахождение в карте
