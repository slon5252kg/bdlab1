# Розроблення функціональних вимог до системи

## Модель прецедентів

### Загальна діаграма прецедентів

Рисунок 1 ілюструє загальну схему прецедентів та визначає ключові взаємодії.

![Діаграма](//www.plantuml.com/plantuml/png/RLD1QnD15BxFhnZIWwSeL1gBXz8sRK-Ub7eIP4o6TTbafyniA465jh5wAKHAQC6BYFw0PKrmcwRrBypy8x_PsGcZRI2xEs--zxxlVMzcKsLCPeD-ZwWaJW-OP7tAEfcGBx9XZrDso9Neys1pe7Y7AKxV4OhVDkiaaHI3jDiMFI7fojxENcltiTiJiijb7LzRR-q-MQlYMrAAmpgysbhVtbab7mYfIEdBMCNspHHjw7DpeQUwi4ypqeNEpUS6NOaa6zRevppQLxn6NsB_IC_Cn1oR4tFqy5Mgl-fRX4eR20gePFYcD-1rZQrkFqvT1S3rZJdHC_jiwXpa2v3V82TvovAOa0Eqoo8ExCHSc4kgVu71LZz3Qe4_rXHfjpNb7pDgEAUMlkstNqEs8_mEii9fn5T9GJc7o97bR_oVzKn4NkYFofGhbrDGS-nwXF052E5c8FIdBQVdvfCJ_FjVbohPEG2bERr7QLka6Kypn_eDQKX5ZzTchAVq4TNdkeJYfScs4hIFOVq2m2b4vaq00bllwFlYNMwQZw7KUzI4ex9Qx4m3oldTQMDteSkAqP-iPdF3p-0f3Qqm8tnXabYDG_JIU-3X-ocwcO85I4By0GGijCi2AwSde0SS_Km8gUHxg5i0k3nb07aT03-Wc39AmEqSVf-Xovdhb5PJkyRoAk1_l-7lZkS9GviyxUAE_mK0)

*Рисунок 1: Загальна схема прецедентів*

### Специфікація прецедентів використання

Відповідно до схеми, система розрізняє 3 ролі акторів:

*   **Відвідувач** - неаутентифікований користувач. Може створити новий акаунт або увійти в існуючий.
*   **Зареєстрований користувач** - аутентифікований користувач. Має доступ до функцій роботи з медіа-контентом.
*   **Адміністратор контенту** - аутентифікований користувач з розширеними повноваженнями. Має доступ до управління іншими обліковими записами.

Рисунок 2 деталізує доступні дії для неаутентифікованого відвідувача.

![Діаграма](//www.plantuml.com/plantuml/png/LP3DIiGm58NtUOhBxESLPC2jAq5NWeIPC1IqXQRTsyQVPQL8r_e6fRPGYkapdFj6tgW1PnF8pNVEbsHd2vqNvVsTqliYosc3bZkC6CBA3WDwVjcGjdITs4G8fKfhzjeQGTynyHjNNFE3OC_SSNEJueDh35XbDi73SqFmMCC8drW9FHQX7Rpat4_rrVdjfJd-AsxvAVW9emIumXmacF25MGIlxC8k5CZ9ev1Br1EMOFuDnEkZZvQBx9YaIlqzXRQ7xLcKdyuYkZFfGJxd6m00)

*Рисунок 2: Схема можливостей Відвідувача*

### Схема прецедентів для Зареєстрованого користувача

Рисунок 3 показує функціонал, доступний зареєстрованому користувачеві.

![Діаграма](//www.plantuml.com/plantuml/png/XPHHQzDG5CVVyoakzK5zADXIHMMKQSKFiDatGMxJaxOqIyPDYg88syhGjy4e3dnGmIyGv-fgJViPplr6_kzD5cjafg7jlUVyStxdVtB9TXHB5K_sV2SQZu9zgUIUw4btF53X9EXtGZzKueRtm5mRYab4hen8l744Fe_BUcfuTpmlouMgJogFj-xTR_PQDlv8gV1b7cvwBLms_3GCujtHQnADLh7FL3qVb8sIpuOZTnnG58c6ZUvaV1MG4isxpbl7aMwC-sfynea-uBcUwKDzXDMQppdX5I_uf-0bhn5QsDJK9FIxcf2HsA51Do8qvuy6mxZdJyXn5Bcn30O-eUX7b5df8vwRtxe-p4fWct9Io-UIJmdgBr1_upK4YU1BK3VlnZfz7jpYKxu4ViOf0XVwWpwnqXGYx3Yf6nE0JFK1S0aIYzksrMxdHGTZeY1sIjYPgGIfzGlKIOcifuPxTgKmxV4Ff7BjoemAt--ytkp3UBc9FfT6_wS5HJAcKWEVuVazvhgy1ho2uMFRP86zXeJzUS7Q9QdSOOdrAU_t5y__QpP5AN0jnpg-o4w3FgussTtl_slob1UcHWNugtbqoEUQQjOJyWai7EIhirYlj_zwsCNKIndnK6njqIii-r6xxHG3gvHbzYfbfhCgsJR-yLRv3G00)

*Рисунок 3: Функціонал, доступний зареєстрованому користувачеві*

### Схема прецедентів для Адміністратора контенту

Рисунок 4 відображає спеціальні можливості адміністратора контенту.

![Діаграма](//www.plantuml.com/plantuml/png/dLDDQnH14BtthoXsBte8x4gY8c59L3oB7pSldPcQpR2ptT8zI_n0YBkW7WGzoEOYUCWV66E2IvAT_8NgVsHrTrZ62KHm1gRfLw_UUrtqRDbIcd8oBeGTvUgbD78CEp8P3OsUgFI1BhI1RfPbQNQdmPXOJAH5U2k0d_jN-9ZTJk_6cZOfcaiyaNAzrmlujZ5wxnBUaFuDy2EjogVv6uJ--ceVMJi5kpGad-tcoKYXjT0Fw9FeRnGQkBKXtWaXavBxElILZkdSpMdfvkwzcxfzgjoKQhSFT4ermrCwyLytwu2qi9sESmNT8X_kbg-nAFIU40QJKgfXWIptdNkEtOpEt6UWggtDXID6buny2VfijmYbK70VcNpKYODRZP4p_fVE2tM33kd2duZ1CuOYdnF-35lkuyA2pca1z9jP5rw4LmPkXjC-jsZ2YKKhqI6RpLZlv9eCLFa4tvXJqIcFSH7W3sv-DKDDlwXkP72pwFyG2opHfu0kzhDUbhLo7CIvK0NiNdl5QwByy32RB3sqYXxc-ebx3bOQqVonqMFTSkUB4s_0sjgWEPr6qBygS0ysD_5LYIgrWu68al_cRV7AVzqV)

*Рисунок 4: Схема можливостей Адміністратора контенту*

## Сценарії взаємодії для Відвідувача

### Реєстрація нового користувача (UserRegister)

*   **Ідентифікатор:** UserRegister
*   **Назва:** Процес реєстрації нового користувача
*   **Актори:** Відвідувач, Система
*   **Передумови:** Відвідувач системи не має існуючого облікового запису.
*   **Результат:** Створено новий обліковий запис користувача, готовий до використання.

#### Нештатні ситуації

*   **InvalidDataException**: Надані дані не відповідають очікуваному формату або правилам.
*   **DataMissingException**: Не всі обов'язкові поля реєстраційної форми заповнені.
*   **AlreadyRegisteredException**: Обліковий запис з вказаною електронною поштою вже існує.

#### Основний потік подій

1.  Відвідувач ініціює процес реєстрації (наприклад, натискає кнопку 'Реєстрація').
2.  Відвідувач заповнює реєстраційну форму (вводить ім'я, прізвище, email, пароль).
3.  Система приймає дані для реєстрації.
4.  Система валідує отриману інформацію.
5.  Система перевіряє, чи не існує вже акаунт з таким email.
6.  Система створює новий запис про користувача в базі даних.
7.  Система сповіщає користувача про успішне завершення реєстрації.

*Діаграма послідовності для UserRegister:*
![Діаграма](//www.plantuml.com/plantuml/png/hLJTJjH05BwVfpZ12o7XGXEls1lmnyGBlT0d6EcuJkYsf5jG51EMLS24k8Piy4QZl46jLfQoXLSuyqP-fxED9Ap62wRPpPapv-VxlkdfOZVLIRhM2LLtnKQhEj4TUggNLzf9l1O5T-8mJkZQCoFFXGYzdDfrcsxGQqLOjoybrCkVnKbWaed_Hhrg_rAIn2ycxblrgjttuoXzObyPklbd_qXt3EAj3jKRfJRvm1toJyxbt_KvvypjRggQXreWtk7A7ReT_3wu8RajBjpGzTmshCoxQPOhsDiySZqkOGs9IxZE-9nBrwSP_dOfQJ0prvBg1-XtXkuZdEqJ88olky4yyRdRmkQOSvoyvsAUJ4VRK0vGO0iffsw_9U2Ff2jw5ppcR5DAViNvY4-m5oIedGa36CWPJ2FmoID1tAdNGD9oF0LoYacohz9IKPmQIcpxUIhNeh4KVmQUNtpA8n6Fk4A7FK0IIIeue8hGwpVK5nGF6r289Iyzc9rDh0nIYnp2diTm_q3uc4ZDFeZMTMY3kphLzrukczNKnj6SCb50WalLzBaGZb8A6Ww4op5dlZfNde_GHtsuleiRaYEc51D8tr4TB5haLyNtYwVP4yg--60AB64er1xQRjT6xVzcE4zkbqSalBZorvVLBs8Vssqq8Y0J3zJqBz9LyVfuiKsEvE8Y2j1P2XEZWut7fcsxgKbCy3TIHsY2KG0X6JEk_6NmYRyakOooSJNAuSLlDHFwLb9vxCcNil5pqGoqy3cNmI64z60UkZr1ENMWM__uAiIhQX70yONx3G00)

### Аутентифікація користувача (UserLogin)

*   **Ідентифікатор:** UserLogin
*   **Назва:** Вхід користувача до системи
*   **Актори:** Відвідувач (що має акаунт), Система
*   **Передумови:** Користувач вже має зареєстрований обліковий запис.
*   **Результат:** Користувач успішно аутентифікований та отримує доступ до функцій системи для зареєстрованих користувачів.

#### Нештатні ситуації

*   **TooManyActionsException**: Вичерпано ліміт невдалих спроб входу.
*   **DataNotFoundException**: Надано невірний пароль або email.
*   **NotRegisteredException**: Обліковий запис з таким email не знайдено.

#### Основний потік подій

1.  Користувач відкриває форму автентифікації.
2.  Користувач вводить свої облікові дані (email та пароль).
3.  Система приймає запит на вхід.
4.  Система верифікує надані облікові дані.
5.  Система перевіряє існування акаунту з вказаним email.
6.  Система авторизує користувача, надаючи доступ до захищених ресурсів.
7.  Система інформує користувача про успішний вхід.

*Діаграма послідовності для UserLogin:*
![Діаграма](//www.plantuml.com/plantuml/png/hLHBRXD14DttALfY0pkGMCMRX4zsP05SeB4RCuezROqdGC18jYSaMKGoGiXi-8WRZAqO6t_6LwYw4VNAZcm9WLYaeupwywhVUrNLtcscBacFwZNJF8pYXajStJvpvSDg4exYolrG2uczyTpZRmlXocdqCagFxLjZPTpx8q37wYma5P-izs_hqFsz90clrjjtTUZsVeZJ9z4RR-zirWUkxWKVkPfvPqoBFdAVBcc8BsSqf9pFMaPzc1sxFfrocoPwzido2HMod7DcAPUuBere8Ty9dmXsAfXJxlFdaaPBJ27n4-xoXVLr5zMiG7DBIy6rvMp65oMe-26OZjurfxo5sE_A-GjhOQMna2rnaQK5BXZoUqXRqum0NWdW3F221ZHJFGMyMH6HYyn-oSGXzJQ9gYzIPDR9CFH5K3zfjl88WX6VGwVyWumxwY1RU-lj6A6Sy1beuKH0XLMwkHntWL-gku7gH0eaMzRSV1h28nSVxqd1Gzny-Bhi6vZTCZwkM0Wpwbpl7K4tjxadTcJIeGNA0pAPzP1xv3f3xb6AyIgzr-NlstR-K8TD1Jfw0TOIAmMwH0DG0Ny78Ntigr4pzOcl_ByziEZM589W5lsotIIzw_BrzOfO072bIKCo1-9WkojXvu5BdLZQnrlycviF-WGARTOnPnitsizNBufoRTHJMcoU3w3Q9bRcw9W-dwzKRRhx7myqDCokA94Vczy0)

## Сценарії взаємодії для Адміністратора контенту

### Призначення іншої ролі користувачеві (UserRolePromote)

*   **Ідентифікатор:** UserRolePromote
*   **Назва:** Зміна ролі існуючого користувача
*   **Актори:** Адміністратор контенту, Система (можливо, сповіщення для Користувача)
*   **Передумови:**
    *   Адміністратор контенту аутентифікований та має відповідні права.
    *   Цільовий користувач має активний обліковий запис.
*   **Результат:** Роль цільового користувача успішно змінена.

#### Нештатні ситуації:

*   **RoleNotEnoughRightsException**: Поточний користувач не має прав адміністратора.
*   **NotRegisteredException**: Цільовий користувач не знайдений в системі.
*   **RoleAlreadyHighestException**: Спроба призначити роль, яку користувач вже має, або найвищу можливу роль.

#### Основний потік подій

1.  Адміністратор контенту вибирає цільового користувача в інтерфейсі управління.
2.  Адміністратор контенту обирає нову роль для цього користувача.
3.  Система отримує команду на зміну ролі.
4.  Система перевіряє повноваження адміністратора.
5.  Система перевіряє існування цільового користувача.
6.  Система перевіряє, чи можлива зміна на обрану роль.
7.  Система оновлює роль користувача в базі даних.
8.  Система повідомляє адміністратора (та, можливо, користувача) про успішну зміну ролі.

*Діаграма послідовності для UserRolePromote:*
![Діаграма](//www.plantuml.com/plantuml/png/hLJBRjD05DtFLup41dOWiMetBQY8LHVX2qmof5OJJpIP08KWvI7na2A24Ce2qG9_O8m3XgJc5-xy4UUE7Me9HmAf4-NXwtiUP-uuUtqR63leTaJ_E8nwWGcwydxGF6uRFOXQjtL76tdbWU9NfIDesl1XQ4_aKo6nRlq5yAkufqrBcR9-tIzVtpT6FohBD_tovJiwilV29qhUkBW-3BeA_M7G4S-46D8RIcdj5dJk5cxi9cv4iPjGxaQIVbAEyeIM_EccG-7ZYHr9RocZBvJvvdU-4JypZvzIWk8BYYM8LsukwNl1Jvb4KuxQOfSvpgeCvxYHkEccOxRBrZupfTTVKppq66ym0-6qrELRGAV0uYl-eyPSLRMFjCJraXB47Bavet-nPg4CZcyS4pWOZhTj2SMx8j9MIHEsZonF9i0Iz85ou5UKCHDyGEib48nYJsvC6UyC2iz1ETyHT0gr59JZJPkRKGvBh469bE9gGtVKeRO7aHwqZngirpzut5Gz6-hecb1HIx8JKP-DZOFJpw9CnTAyinmNxw-KryxjyYA-hoFtI0o9GVI3Kh_fEUT5rePgXtshZ6hzUr9QNnWhnpMhEtANbUfJSJvzRrMxcDu2YH9WNZ6EiiqSzpj61QsJkn1NVRijt5bn5a7_6i4sJyBMAG5noaULJTAA7wFI0PGJlqzfzL3NRCd_F_ww9_RW6Vzmlm40)

### Усунення користувача (UserDelete)

*   **Ідентифікатор:** UserDelete
*   **Назва:** Видалення облікового запису користувача
*   **Актори:** Адміністратор контенту, Система (можливо, сповіщення для Користувача)
*   **Передумови:** Адміністратор контенту аутентифікований та має права на видалення користувачів. Цільовий користувач існує.
*   **Результат:** Обліковий запис цільового користувача видалено (або деактивовано) з системи.

#### Нештатні ситуації:

*   **PermissionDeniedException**: Поточний користувач не має прав на видалення.
*   **NotRegisteredException**: Цільовий користувач не знайдений в системі.

#### Основний потік подій

1.  Адміністратор контенту вибирає користувача для видалення.
2.  Система отримує команду на видалення користувача.
3.  Система перевіряє повноваження адміністратора.
4.  Система перевіряє існування цільового користувача.
5.  Система видаляє (або позначає як видалений) обліковий запис користувача.
6.  Система сповіщає адміністратора (та, можливо, користувача) про успішне видалення.

*Діаграма послідовності для UserDelete:*
![Діаграма](//www.plantuml.com/plantuml/png/hLHFQnD15B_FftZKIt8G0WM57gIDQKz5Ylq4w-viN9BinjaDMaH84z0AGYH8JgBquZcDIPicRV8LtdmZVw-Rib4NxQ4BsTsPURy_xpUpsOuJnoIjHbt5jI1iEiPfq0l7hLLDr0gzfr4zClHWhxBtQ7TphIBMhrewT3MzLOHhnvZeTLfRqRfvM3igrriwNNAJo9GZuscJ5fJhO9SbsWzylH-4-Z-hVvhH9V-nxqWD7S1wu0PD9qpoITOA_iNpB4h-rl5zVzFrilLCGDPSjrHIxvHof3_QuCyyvYixu6ixiCUsOziyj1rUs3RnZ1UOxl14xhQxGKvCEruZ25KpimUAKvu2AdLNF9GgEZoA4zrGwgQQ7Zv9ORH5tESfdw5UPBw819G4BW8ymkG77X8ipMsFC9xYTSXpiG0JlJN6L48elm4B3dJHNL6A3m36jaju3FE8KlZlHDzv0g89Zn15s_Q4R0co4I2u0tv-2oSCycF3KuL8dKnGVPb8u0uknLz1SGxzgH315QHE012GEBJ7F9K8CF4UZBqjnNsmGqEaLxuN90sDePB6jRG3AWYLz7lZLkHvL5I50sqQGHm7KLZHOQ2ztJUkRYOO5fKEFHA7Tun0-kFhT7DMpOj5RD0diORVJrxaR-Hz9V4ZamFgCbUCX8ZuGZZuaiSIc1Ih0hw1vxeQe4DpznpwjmT6Cg02tiwaIz3YTGQhS2_7hKYymD8S3cUPlmiKBSLVnfrz0QVfeK9l7xDTawr5vqlCdaWdUKTs6uxnV_SB)

## Сценарії взаємодії для Зареєстрованого користувача

### Додавання медіа-контенту (ContentCreate)

*   **Ідентифікатор:** ContentCreate
*   **Назва:** Створення нового об'єкта медіа-контенту
*   **Актори:** Зареєстрований користувач, Система
*   **Передумови:** Користувач аутентифікований і володіє необхідними дозволами для створення контенту.
*   **Результат:** Новий медіа-об'єкт успішно додано до сховища системи.

#### Нештатні ситуації

*   **PermissionDeniedException**: Користувач не має дозволу на створення контенту.
*   **ContentIdExistsException**: Спроба створити контент з ідентифікатором, що вже використовується.
*   **InvalidContentDataException**: Надані дані контенту не пройшли перевірку (невірний формат, відсутні обов'язкові поля).

#### Основний потік подій

1.  Користувач активує функцію створення контенту.
2.  Система відображає форму для введення даних нового контенту.
3.  Користувач заповнює форму та/або завантажує файли.
4.  Система перевіряє права користувача на додавання контенту.
5.  Система перевіряє унікальність ідентифікатора контенту (якщо застосовно).
6.  Система валідує надані дані та файли.
7.  Система зберігає новий медіа-об'єкт.
8.  Система інформує користувача про успішне створення.

*Діаграма послідовності для ContentCreate:*
![Діаграма](//www.plantuml.com/plantuml/png/hLNVJXDF5BwVfvZmk-5tOTGBbN1X46eC2I4an0SOjrESqExMsG4XneG_1haWO0Y1n6YCRx1KYwNGyWfdtiXlpiAos6guO3TDftE-yttdctDsEv4wPTrIeoxIHHCtbLKD-Kf5YmisMOghKqaziVA_sgDmbn2fVhEauqZBTqBYUcPjyZR7LfHTdAyhfrzOjPe78vVOoSHMjSqXisevZyoOcfuniIu7AwPHP1RnF-lHZsjFQZN6pA5w4vccYbsPPhAEd070W2--63QRE3qiFgOV5l6o069HDFQ0OvF9oc2g2dSHBcNEc_gojkAz42gSZ1oX8yhy6hNzWL_t6rZrgKKPzQX3fvAwrCTMXqER8U0_ZaYLofSfI9hNvi3pFOTHcyufOz3yQkfqGuW0blUUSf8Sb_I9ki1rgEKt_O7q7y3SmzQMF_IxaZbQBDl6Ti_lSHLO1EfUgACWp0K29KpG1GhO01tddbDd29N8Csxcxlj3-Wc5O-0oEe77WuB5Rqh4pb348DbVoy098hvxa-Q-f5-8yjc22KANxh4yfJFg3Atj6xLPi8MpMVDxIA0BR33FqEvG9c8CYxHcuRKBSw9m2Vg2eaw2IfxO0-rsg0AV7cKmHntcoBWBU-E2la8LfyAs6UPtg5-e_-DKHkUqRPWqDKbSqR7HrUShaMuw_FnVwBWgGtctz1e60ytfGl4CybYprHqvNRaZbv_BauKEIMvD5mpd497K0bzR1bq0q2ynEfN4JiTk6hPCwjBRcjjd3nWqxdee1oUO1KloQd67ZSi70z-0bIK67wNHwNXPrKtrqbP5ENLRIqTq73e6KpyWpwOm-VpUk2bpdLsy0hQmNpmRLrFTbrYlOtdejuFJOTCrWPBmV_4R)

### Пошук медіа-контенту (ContentSearch)

*   **Ідентифікатор:** ContentSearch
*   **Назва:** Пошук існуючого медіа-контенту
*   **Актори:** Зареєстрований користувач, Система
*   **Передумови:** Користувач аутентифікований в системі.
*   **Результат:** Система надає користувачеві список медіа-об'єктів, що відповідають критеріям пошуку.

#### Нештатні ситуації:

*   **InvalidContentIdException**: Пошук за ідентифікатором, якого не існує в системі.
*   **InvalidSearchRequestException**: Введені некоректні або несумісні параметри для пошуку/фільтрації.

#### Основний потік подій:

1.  Користувач ініціює дію пошуку контенту.
2.  Система надає інтерфейс для введення пошукових критеріїв та фільтрів.
3.  Користувач вводить пошуковий запит та/або застосовує фільтри.
4.  Система перевіряє валідність введених критеріїв.
5.  Система виконує пошук у сховищі контенту за заданими параметрами.
6.  Система формує список знайдених результатів.
7.  Система відображає результати пошуку користувачеві.

*Діаграма послідовності для ContentSearch:*
![Діаграма](//www.plantuml.com/plantuml/png/hLFB3j905DtFLqpY1bRkwOP4NR3LBsYW20cs28DnmO82GHT44q9AOdHXuWTKqafvjFp2lN_akHrZ8CY6ID8mcJcFSswdzQ5n1sRqfgVKc3OKyuHINdF8KwmAsb9CEMMqrtIW0bjPUJIJ0_umLYLRrJGjAEU85tW-yLfJ8WjDPt0-0dtWcIC6tosVKZfHF1RUDnWa58F34IHmn1EU0x3dy8R_G41OhB0kO99XVmcOWAmHGcxqKqqxOC42FnH9dacSEG8TUGaIy7VIh-1-12uHoaLSKR6X88rj-3dA3uod1ztN7QEVjDikVeg-0lcBZi0YhqQJ509JYl7as42UJDfWGqRxkQOmiDGsbN-1SIJ6CfSOkLARzsfqgjBmtxczRkkLvmwQdPVUsv4tD2_UDxs-wGP-LNb-IqiwMoaJVUXULz9_TgL-Bfd-Io5TeVDDtd9gkl6yYhfVBarne4MC3j0_0L4Q21pQjAT4O5JyxViiy8tdcqRhJjSVvHnFzds7yfxa0g1hETqTqk02sFGSqTOfvuDL0j1F6JYgojMzXLFsp_i8s9OZvz5lBUWhLKS1-Ln_0m00)

### Зміна інформації про медіа-контент (ContentUpdate)

*   **Ідентифікатор:** ContentUpdate
*   **Назва:** Редагування метаданих існуючого медіа-контенту
*   **Актори:** Зареєстрований користувач, Система
*   **Передумови:** Користувач аутентифікований та має права на редагування конкретного об'єкта контенту.
*   **Результат:** Інформація про вказаний медіа-об'єкт оновлена в системі.

#### Нештатні ситуації:

*   **InvalidContentIdException**: Спроба редагувати контент за ідентифікатором, якого не існує.
*   **PermissionDeniedException**: Користувач не має дозволу на редагування цього контенту.
*   **InvalidContentDataException**: Оновлені дані не пройшли валідацію.

#### Основний потік подій:

1.  Користувач обирає функцію редагування для певного медіа-об'єкта.
2.  Система надає форму з поточними даними контенту для редагування.
3.  Користувач вносить зміни в поля форми.
4.  Система перевіряє існування контенту, що редагується.
5.  Система перевіряє права користувача на редагування цього контенту.
6.  Система валідує змінені дані.
7.  Система оновлює інформацію про медіа-об'єкт у сховищі.
8.  Система повідомляє користувача про успішне оновлення.

*Діаграма послідовності для ContentUpdate:*
![Діаграма](//www.plantuml.com/plantuml/png/hPJ1gjD058RtynG3RgwlSE_cWdNHdQyGRAu6xaqkxIWkkcXIq2vA0wL446tn3MAjsZQPz1NEUIF_Cp5IIeCWxIR3pFd_-VuvCxqT6AzltZpSApMaZvJpY7xmWcDECAfeJJbPsj9EqvugJ6tTqbWM-CDGERMwrhIaRrWRONQXeJlmUyvufiMEDZ3v3arjPZbrPXWaMBHYToCMSzeUcxWIsZkWf8OuqVrHMO35q2KyrVIBIiwaMjDQkvqjPpSIxclD3cb9-L2aApWBtnge8qwnAGOnsN-WXf7nTJzuzThe9tTt7dwAFgFe9nM0X5AJXVC4cjoHvxhcWs_kpYMzLlJfs1RSMiff3uTITplE0hEYfXroe8mgTTKDtthtGUzP51e_DDtUytSl_KSJHE5JvOSzBMZdaz51phMXoriQSwbmNvmvsjAKyPIgXi7rfU2qXK5TlV3x3y5WW5GTFmpyjf1pA0eqUyFZ-j9PTs4BTwJPKVClbwb-0_YwJ5dxfgUTwdZ6QucnR2nuXXYDmVadif9AYOnl2SNVpbOQXn1ZcF54mfoGkTx-xmkF7fMw1R7yIVm6)

### Видалення медіа-контенту (ContentDelete)

*   **Ідентифікатор:** ContentDelete
*   **Назва:** Усунення існуючого медіа-контенту
*   **Актори:** Зареєстрований користувач, Система
*   **Передумови:** Користувач аутентифікований та має права на видалення конкретного об'єкта контенту.
*   **Результат:** Вказаний медіа-об'єкт видалено з системи.

#### Нештатні ситуації:

*   **InvalidContentIdException**: Спроба видалити контент за ідентифікатором, якого не існує.
*   **PermissionDeniedException**: Користувач не має дозволу на видалення цього контенту.

#### Основний потік подій:

1.  Користувач обирає функцію видалення для певного медіа-об'єкта.
2.  Система запитує підтвердження видалення (опціонально).
3.  Користувач підтверджує видалення.
4.  Система перевіряє існування контенту, що видаляється.
5.  Система перевіряє права користувача на видалення цього контенту.
6.  Система видаляє медіа-об'єкт зі сховища.
7.  Система повідомляє користувача про успішне видалення.

*Діаграма послідовності для ContentDelete:*
![Діаграма](//www.plantuml.com/plantuml/png/hLJ1RjD04BtlLupQ2vn2aw9AgR4gQ95oG-eNEFOcNTLPH_QsK0XIaah00H6fgeA418W_C542RjAulp3xHynkqX2fXWF2kOpVp9jvRtRZlKHviJffXImv5hBjnLuBwfv_t8oZ4nayYS8eXir6O7vihSJpbJWLwWnUCQ3dyHs6VHQvA0vulC3h8HLQz6aaLH5sA5vosDgsxuT7NX0z5x893IzC-79Il1nHzYlyuOD5eV5m2tFVtzcoyC5A3j_PzYi-UyrO1pzYghiuqPUwf_iKvJZ25EUOuHNW57E2CfiwDmdzjiFiYbWLl-1tIdK9l0IYtUWtUgW_08w8EwOUCvnGdxaUs3uKz0rWEkqI-mApTRwjmAcLqb-DNwSPqbSzn3418whgqf0V-fp8ToVk6cVV5i89kyQqOzY6HQyZqjdL0s9IqADwQ-sFMcMaECIYUQIOaxGz2Oaw2_cZ3TyiixePLCgDScF3TUekJSXfM4P2ffXMdLBTTKg6uW8m_BJU6F0dK9nIOORNKDi7cZyX5ES4Nk7OMic9vmZtNasUUg6WuvEAIrKB3bxulAr49Eyx9U4oBWCmAbcXIRmnIpOMmJGlMDV_y_WP9zGwjtjFpK7gzvYl503bPdfGe63fyncFMo99oDW-buB_pUV5RGlZiUYg430oryNAdVtUH0vqQNeK3lKxi_EYVVph7oDgipqIIT-FNm00)