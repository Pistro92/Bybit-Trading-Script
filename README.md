# Bybit-Trading-Script
The script automates a fairly simple trend-following strategy that uses data from a Heikin Ashi candlestick chart. It detects trends, places orders and also places a stop loss which gets updated with each new oscillation. When run for extended periods of time it tends to yield negative returns, although I'm fairly certain that it should be profitable on newly released coins and it could possibly work well when paired with a news trading approach. It could also serve as a template for a more complicated trend following logic.

When it comes to usage, all you need to do is create a Bybit API key and paste it into the script itself. Bybit offers a demo trading service so if you want to test the strategy first, without using real funds, you need to create a separate demo API key. Other than that, you can also change the chart timeframe (the lower the timeframe the higher the contribution of fees), the coin you want to run the script on and order quantity. There is no option to change leverage as by default it is set to use 99% of account funds, which translates to fairly large drawdowns. Also, make sure to install all dependencies listed at the top of the script.

If you're interested in purchasing the script please use the donate button below:

<div>
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
  <input type="hidden" name="cmd" value="_s-xclick" />
  <input type="hidden" name="hosted_button_id" value="PM4VDN98TJF3G" />
  <table>
    <tr>
      <td>
        <input type="hidden" name="on0" value="Your email adress"/>
        Your email adress
      </td>
    </tr>
    <tr>
      <td>
        <input type="text" name="os0" maxLength="200" />
      </td>
    </tr>
  </table>
  <input type="hidden" name="currency_code" value="USD" />
  <input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_buynowCC_LG.gif" border="0" name="submit" title="PayPal –wygodne i bezpieczne płatności za zakupy w Internecie." alt="Kup teraz" />
</form>
</div>
