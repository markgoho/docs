---
ms.openlocfilehash: b4949218acc89828772bf2bea3998dfde3a10e95
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/05/2022
ms.locfileid: "147080454"
---
Ссылка на ветку или тег, через которые был инициирован запуск рабочего процесса. Если рабочий процесс запущен по триггеру `push`, здесь указывается ссылка на отправленную ветвь или тег выпуска. Если рабочий процесс запущен по триггеру `pull_request`, здесь указывается ветвь слияния для запроса на вытягивание. Если рабочий процесс запущен по триггеру `release`, здесь указывается созданный тег выпуска. Для всех остальных триггеров указывается ссылка на ветвь или тег, которые активировали запуск рабочего процесса. Это значение задается только для тех типов событий, в которых доступны ветвь или тег. Ссылка сохраняется в полном формате, то есть `refs/heads/<branch_name>` для ветвей, `refs/pull/<pr_number>/merge` для запросов на вытягивание и `refs/tags/<tag_name>` для тегов. Например, `refs/heads/feature-branch-1`.
