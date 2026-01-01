<div class="planner">

  <!-- Header -->
  <section class="card header-card">
    <div class="month-year">
      <select id="month"></select>
      <select id="year"></select>
    </div>
    <div class="starting-balance">
      Starting Balance: $<span id="startingBalance">0.00</span>
    </div>
  </section>

  <!-- Income -->
  <section class="card">
    <h2>Income</h2>
    <table id="incomeTable"></table>
    <div class="total">Total Income: $<span id="incomeTotal">0.00</span></div>
  </section>

  <!-- Savings -->
  <section class="card soft-card">
    <h2>Savings</h2>
    <table id="savingsTable"></table>
    <div class="total">Total Savings: $<span id="savingsTotal">0.00</span></div>
  </section>

  <!-- Bills -->
  <section class="card">
    <h2>Bills & Fixed Expenses</h2>
    <table id="billsTable"></table>
    <div class="total">Total Bills: $<span id="billsTotal">0.00</span></div>
  </section>

  <!-- Debt -->
  <section class="card heavy-card">
    <h2>Debt</h2>
    <table id="debtTable"></table>
    <div class="total">Total Debt Payments: $<span id="debtTotal">0.00</span></div>
  </section>

  <!-- Overview -->
  <section class="card overview-card">
    <h2>This Month’s Financial Overview</h2>
    <div class="overview-grid">
      <div>Opening Balance</div><div id="openingBalance">$0</div>
      <div>Total Income</div><div id="overviewIncome">$0</div>
      <div>Total Expenses</div><div id="overviewExpenses">$0</div>
      <div>Difference</div><div id="overviewDifference">$0</div>
      <div>Total Savings</div><div id="overviewSavings">$0</div>
      <div>Balance Forward</div><div id="balanceForward">$0</div>
    </div>
  </section>

</div>