# Currency-Coverter
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

  <h1>💱 Real-Time Currency Converter – Summary</h1>
    <h2>🔹 Purpose:</h2>
    <p>
      To convert an entered amount from one currency to another using live data, and to visually show the associated country flags for each selected currency.
    </p>
    <h2>🔹 Key Functionalities:</h2>

   <h3>Currency Dropdown Initialization:</h3>
    <ul>
      <li>Populates two dropdown menus (for "from" and "to" currencies) using a predefined <code>countryList</code> object.</li>
      <li>Sets default selections: <strong>USD</strong> (from) and <strong>INR</strong> (to).</li>
      <li>Attaches event listeners to update flags when currencies change.</li>
    </ul>

   <h3>Live Exchange Rate Fetching:</h3>
    <ul>
      <li>On page load or button click, fetches real-time exchange rates from the <strong>Fawaz Ahmed Currency API</strong>.</li>
      <li>Ensures the entered amount is valid (defaults to 1 if not).</li>
      <li>Calculates and displays the conversion result.</li>
    </ul>

   <h3>Flag Image Handling:</h3>
    <ul>
      <li>Uses the <strong>FlagsAPI</strong> to dynamically show the national flags corresponding to selected currencies.</li>
    </ul>

   <h3>Event Handling:</h3>
    <ul>
      <li>Prevents default form submission behavior.</li>
      <li>Automatically performs a conversion when the page loads.</li>
    </ul>
    <h2>🔹 Overall Workflow:</h2>
    <ul>
      <li>Load page → set up dropdowns and default values.</li>
      <li>User selects currencies and inputs amount.</li>
      <li>Button click triggers currency conversion using the API.</li>
      <li>Results and flags are updated live in the UI.</li>
    </ul>
</body>
</html>
