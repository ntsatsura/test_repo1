# test_repo1
#### _here we will describe how we work with our repo_

## Различие между командами git pull и git fetch

### ***git fetch и git merde***

**git fetch <удаленный репозиторий>**
- осуществляет получение актуальной версии изменений с удаленного репозитория на локальный, но без объединения с рабочей (основной) версией/веткой проекта, а путем создания копии (множит изменения)

**git merde <удаленный репозиторий> /<ветка>**
- объединяет изменения, ранее полученные с удаленного репозитория с основной веткой локального репозитория


### ***branch***

**git branch -r**
позволяет посмотреть все удаленные ветки

**#** - префикс ветки удаленного репозитория

**git switch <название ветки>**
переключиться на эту ветку


### ***git pull***

**git pull**
- получение изменений из удаленного репозитория и одновременное объединение их с версией/веткой проекта на локальном репозитории
>> *объединяет в себе две команды: git fetch + git merde*
