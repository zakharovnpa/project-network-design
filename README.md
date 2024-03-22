# Дизайн сети предприятия.

## Проект верхнеуровневого дизайна распределенной сети организации.

> Проект на стадии разработки, готовность - 60%


1. Описание инфраструктуры
- в составе организации 1000+ пользователей
- головной офис – 200 сотрудников;
- 10 филиалов по 50 сотрудников каждый;
- 300+ сотрудников на удаленной работе;
- 2 [ЦОД](https://github.com/zakharovnpa/project-network-design/blob/create-0.0.1/DC/README.md) – основной и резервный.
  

2. Обеспечить для пользователей [сетевые сервисы](https://github.com/zakharovnpa/project-network-design/tree/create-0.0.1/LAN#%D1%81%D0%B5%D1%82%D0%B5%D0%B2%D1%8B%D0%B5-%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D1%8B-%D0%B4%D0%BB%D1%8F-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9): 
- LAN в офисах;
- WiFi в офисах;
- доступ в Internet;
- VPN для внешних сотрудников.

3. Требования к дизайну: 
- все подключения между площадками должны быть [отказоустойчивые](https://github.com/zakharovnpa/project-network-design/tree/create-0.0.1/LAN#%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BE%D1%82%D0%BA%D0%B0%D0%B7%D0%BE%D1%83%D1%81%D1%82%D0%BE%D0%B9%D1%87%D0%B8%D0%B2%D0%BE%D1%81%D1%82%D0%B8);
- решение по VPN для внешних сотрудников должно быть отказоустойчивым;
- доступ в Internet отказоустойчивый;
- предложить решение защите Internet трафика;
- спецификация и привязка решения к вендору не обязательна.

4. Итоговая документация:
- схема организации связи между площадками;
- описание предлагаемых [сетевых протоколов](https://github.com/zakharovnpa/project-network-design/tree/create-0.0.1/Protocols) и [технологий](https://github.com/zakharovnpa/project-network-design/blob/create-0.0.1/LAN/README.md#%D1%82%D0%B5%D1%85%D0%BD%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D0%B8) для организации [отказоустойчивой связи](https://github.com/zakharovnpa/project-network-design/blob/create-0.0.1/LAN/README.md#%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BE%D1%82%D0%BA%D0%B0%D0%B7%D0%BE%D1%83%D1%81%D1%82%D0%BE%D0%B9%D1%87%D0%B8%D0%B2%D0%BE%D1%81%D1%82%D0%B8).
5. Сервисы и документы дополнительные.
6. Опционально:
- решение на оборудовании отечественного вендора.
