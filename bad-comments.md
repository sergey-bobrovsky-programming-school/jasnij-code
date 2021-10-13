// need convert value to string because it may come number from backend

|

V

// Бормотание. Можно исправить на: the value should be cast to string because the server may return either string or number


// Scrolls the page to top
const scrollToTop = () => ....

|

V

// Шум. В данном случае комментарий можно вообще удалить.


// Renders wrapper component
const Wrapper = ({ children }) => (...

|

V

// Шум. В данном случае комментарий можно вообще удалить.


/**
 * Returns checked or not
 * @param {Array} selectedValues
 * @param {String} value
 * @returns bool
 */
const isChecked = (selectedValues, value) => selectedValues.indexOf(value) !== -1;

|

V

// Шум. Обязательные комментарии. В данном случае комментарий можно вообще удалить.


margin: 0 auto; /* this is needed for safari */

|

V

// Неочевидные комментарии. Здесь не ракрыта тема, почему это нужно для сафари и в чем заключается проблема.


//Creates a new AutocompleteResult class
class AutocompleteResult extends Component {...

|

V

// Шум. В данном случае комментарий можно вообще удалить.


/*height: calc(100% - #{$headerHeight});*/

|

V

// Закомментированный код. Данную строку можно вообще удалить.


// Truncates text
const truncateText = (el) => {

|

V

// Шум. В данном случае комментарий можно вообще удалить.


// 1 - private, 2 - company, 3 - public

|

V

// Потенциально устаревшие комментарии. 1, 2, 3 - типы сущностей, это нужно вынести в константы и использовать константы, а не строки.


// possible job status: new, offer, seen

|

V

// Потенциально устаревшие комментарии. Эту информацию нужно вынести в константы и использовать константы, а не строки.


// Mixes action type and data received from server to have ready to use action to be dispatched
const generateAction = (type = '', timestamp = new Date()) => (payload = {}) => ({type, payload, timestamp});

|

V

// Бормотание. Избыточные комментарии. Можно вообще удалть такой комментарий.


// if (report.TIMEOUT) {
//   result.push(
//     <AreaCard
//       key="TIMEOUT"
//       title="Sessions (measured with TIMEOUT)"
//       data={report.TIMEOUT}
//     />,
//   );
// }

|

V

// Закомментированный код. Данный фрагмент кода можно удалить.


} catch (e) {
    // auth failed
}

|

V

// Шум. Комментарий нужно удалить и сделать нормальную обрботку ошибки.


//* Tooltip max width
@tooltip-max-width: 250px;

|

V

// Шум. Комментарий нужно удалить.


responseTimeoutInSeconds: 25, // set response timeout as 15 seconds

|

V

// Недостоверные комментарии. Это значение нужно вынести в константу.