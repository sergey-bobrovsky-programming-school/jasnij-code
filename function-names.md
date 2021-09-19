informParent - sendMessage // отправка сообщения из iframe в родительское окно

validateNumberOfBookingsByPhoneNumberForSlot - validateSlotBookingsCount // проверить количество букингов в слоте

getNumberOfBookingByPhoneNumberForSlot - getSlotBookingsCount // получить количество букингов в слоте

getUsersFromOrganization - getOrganizationUsers // получить всех пользователей в рамках одной организации

loadNotification - notifyAboutLoadedResourses // уведомить о том, что ресурсы загружены

getContainer - getDbContainer // получить контейнер базы данных

getQueuesNotBusyWithCalculationByIds - getUnlockedQueuesById // получить список не заблокированных очередей

updateQueuesSetBusyWithCalculation - lockQueue // заблокировать очередь

updateQueuesSetFreeWithCalculation - unLockQueue // разблокировать очередь

updateOrCreatePosition - upsertPosition // обновить или создать позицию

getOccupancy - get // получить уровень заполняемости в рамках класса Occupancy (Occupancy.get)

getPendingAndNotifiedPositionsByQueueIdSortASC - getPositionsByQueueId, sortPositions // получить отсортированные позиции в рамках одной очереди. Можно разбить на две функции - получение позиций и сортировка позиций.