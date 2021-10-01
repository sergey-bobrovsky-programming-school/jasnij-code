int i = 0;

for(int i=0; i<str1.length(); i++) 

// переменная i (счетчик цикла) должна объявляться внутри цикла, а не снаружи

int s = 100;

for (int i=0; i < 1000000; ++i) {
    s += i;
    ...
}

for (int i=0; i < 1000000; ++i) {
    int s = 100;
    s += i;
    ...
}

// тк переменная s относится к циклу, то объявлять ее следует внутри тела цикла.

let textFrom = 'Some text';

for (const service of textMessageServices) {
    const phoneNumbers = getPhoneNumbers(organization, service);

    if (textFrom && phoneNumbers.includes(textFrom)) {
        phoneNumberNotificationService = new textMessageServiceCreators[service]();
        break;
    }

    // try to find same country phone number
    const matchingPhoneNumber = getMatchingPhoneNumber(to, phoneNumbers);
    if (matchingPhoneNumber) {
        phoneNumberNotificationService = new textMessageServiceCreators[service]();
        textFrom = matchingPhoneNumber;
        break;
    }
}

for (const service of textMessageServices) {
    let textFrom = 'Some text';

    const phoneNumbers = getPhoneNumbers(organization, service);

    if (textFrom && phoneNumbers.includes(textFrom)) {
        phoneNumberNotificationService = new textMessageServiceCreators[service]();
        break;
    }

    // try to find same country phone number
    const matchingPhoneNumber = getMatchingPhoneNumber(to, phoneNumbers);
    if (matchingPhoneNumber) {
        phoneNumberNotificationService = new textMessageServiceCreators[service]();
        textFrom = matchingPhoneNumber;
        break;
    }
}

// тк переменная textFrom относится к циклу, то объявлять ее следует внутри тела цикла.

let url = getGroupMemebersUrlById(groupId);
while (isNext) {
    const membersResponse = await axios.get(url);
    ...
}

while (isNext) {
    let url = getGroupMemebersUrlById(groupId);
    const membersResponse = await axios.get(url);
    ...
}

// тк переменная url относится к циклу, то объявлять ее следует внутри тела цикла.

const maxDiff = 7200000; // 2 hours

const activatePosition = function () {
    if (Math.abs(Date.now()).getTime()) > MAX_DIFF) {
        ...
    }
}

// переменная maxDiff должна быть определена внутри фнукции тк относится к этой функции

const queueId = 'gf9dg9d';

const checkBookingsOrchestrator = orchestrator(function* (context) {
    ...
});

// переменная queueId должна быть определена внутри фнукции тк относится к этой функции

public class BloomFilter {
  public BitSet slots;
  ...
}

public class BloomFilter {
  private BitSet slots;
  ...
}

// все свойства и методы класса лучше делать приватными по умолчанию

int sum = 10;

if (isLocked) {
    return sum;
}

if (isLocked) {
    int sum = 10;

    return sum;
}

// если переменная нужна только внутри блока if, то правильнее будет и объявить эту переменную внутри блока if