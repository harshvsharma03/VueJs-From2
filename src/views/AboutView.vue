<template> 
    <h1 id="date-time">Dashboard</h1>
    <div class="container">
        <div class="sidebar">
            <div><img id="bitcoin-logo" src="https://cdn-icons-png.flaticon.com/128/5844/5844412.png" alt=""> <a href="" class="footer-link">Profile</a><span id="bitcoin-price"></span></div>
            <div><img id="solana-logo" src="https://cdn-icons-png.flaticon.com/128/2645/2645897.png" alt=""> <a href="" class="footer-link">Notifications</a><span id="solana-price"></span></div>
            <div><img id="pepe-logo" src="https://cdn-icons-png.flaticon.com/128/1370/1370907.png" alt=""> <a href="" class="footer-link">Messages</a><span id="pepe-price"></span></div>
            <div><img src="https://cdn-icons-png.flaticon.com/128/9608/9608828.png" id="wallet-total"> <a href="" class="footer-link">Forum</a><span id="wallet-total-value"></span></div>
        </div>
    </div>

    <div class="content">
            <div id="todo-list">
                <!-- Tasks will be appended here -->
                 <img src="">
            </div>
        </div>

    <footer class="footer">
<div class="footer-columns">
      <div class="footer-column">
        <h3 class="footer-title">Profile</h3>
        <a href="" class="footer-link">Github</a>
        <a href="" class="footer-link">Gmail</a>
        <a href="" class="footer-link">LinkedIn</a>
      </div>
    </div>

</footer>
</template>

<style>

.sidebar {
    width: 25%;
    background: #dfe4ea;
    padding: 20px;
}

.sidebar div {
    margin-bottom: 15px;
    font-size: 1.1rem;
    display: flex;
    align-items: center;
}

.sidebar div img {
    width: 34px;
    height: 34px;
    margin-right: 5px;
  border-radius: 25px;
}

#todo-list {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.content {
    flex: 1;
    padding: 20px;
    background: #f7f9fa;
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.footer {
      background-color: ;
      color: #333;
      padding: 20px 0;
      text-align: left;
      font-size: 12px;
      width: 100%;
      height: auto;
    }

    .footer-columns {
      display: flex;
      justify-content: space-evenly;
      max-width: 1000px;
      margin: 10 auto;
    }

    .footer-column {
      flex: 1;
      padding: 0 20px;
    }

    .footer-title {
      font-size: 14px;
      margin-bottom: 10px;
    }

    .footer-link {
      color: #1e90ff;
      text-decoration: none;
      display: block;
      margin-bottom: 5px;
    }
</style>
