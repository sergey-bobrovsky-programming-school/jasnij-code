const isoDate = /^(?:[-+]\d{2})?(?:\d{4}(?!\d{2}\b))(?:(-?)(?:(?:0[1-9]|1[0-2])(?:\1(?:[12]\d|0[1-9]|3[01]))?|W(?:[0-4]\d|5[0-2])(?:-?[1-7])?|(?:00[1-9]|0[1-9]\d|[12]\d{2}|3(?:[0-5]\d|6[1-6])))(?![T]$|[T][\d]+Z$)(?:[T\s](?:(?:(?:[01]\d|2[0-3])(?:(:?)[0-5]\d)?|24\:?00)(?:[.,]\d+(?!:))?)(?:\2[0-5]\d(?:[.,]\d+)?)?(?:[Z]|(?:[+-])(?:[01]\d|2[0-3])(?::?[0-5]\d)?)?)?)?$/;

// здесь можно добавить комментарий с примерами валидной стоки

// maxbsms specific logic for body - no docs, but it seems to work correctly this way
const utf16Buffer = iconv.encode(body, 'utf16-be');
const fixedBody = utf16Buffer.toString('hex');

// здесь комментарий дает дополнительные пояснения к коду

// empty list means all countries are allowed
if (!phoneNumberCountries) {
    ...
}

// дополнительное пояснение к коду

// for AD we generate an event
const { client } = MSGraphAPI.init(
    ...
);

// здесь при помощи коментария мы показываем намерения

// trying to understand if new manager is from AD or not
const newManager = await tryGetUserByEmail(organization, newManagerEmail);

// представление намерений

// Twilio has Body, Plivo has Text
const { Body, Text, From, To } = qs.parse(req.body);

// прояснение

const pendingPositions = [position, newPosition]; // pendingPositions may contain new position

// прояснение

// если тесты были написаны неправильно и не рекоммендуется их запускать, то можно добавить комментарий. Например, Requires to be fixed. Dangerous test. ☠☠☠.

// TODO regenerate content here, should be with updated dates. Segregate logic from email generator

// TODO: remove this, legacy property for backwards compatibility

// NOTE: `startTime` contains milliseconds, but db values do not, so we use this offset to find the proper value
const startTimeOffset = new Date(
    new Date(startTimeForSlot).setSeconds(1),
).toISOString();

// предупреждение

// default regular hours doesn't have capacity, should use default one from queue
const updatedPeriods: OpeningHoursPeriod[] = queue.regularHours.periods.map(...

// предупреждение