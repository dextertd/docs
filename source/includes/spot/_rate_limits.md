# t(:ratelimits)
### t(:ipratelimits)
t(:spot_ip_rate_para_understanding)

### t(:spot_understandingratelimits)
t(:spot_rate_para_understanding)

```
"rate_limit_status": 119,
"rate_limit_reset_ms": 1572114055663,
"rate_limit": 120
```

* `rate_limit_status` - t(:spot_rate_text_limitStatus_understanding)
* `rate_limit` - t(:spot_rate_text_limit_understanding)
* `rate_limit_reset_ms` - t(:spot_rate_text_limitReset)


### t(:perendpoint)
<table class="custom_table">
  <tr>
    <th>t(:row_comment_rate_limit)</th>
    <th>t(:row_comment_path)</th>
    <th>t(:row_comment_consume)</th>
  </tr>
  <tr>
    <td rowspan="10">100/min</td>  
  </tr>
  <tr><td>futures/private/order/cancel       </td><td>1 / request</td></tr>
  <tr><td>futures/private/stop-order/create  </td><td>1 / request</td></tr>
  <tr><td>futures/private/stop-order/cancel  </td><td>1 / request</td></tr>
  <tr><td>futures/private/order/replace      </td><td>1 / request</td></tr>
  <tr><td>futures/private/stop-order/replace </td><td>1 / request</td></tr>
  <tr><td>futures/private/order/create     </td><td>1 / request</td></tr>
  <tr><td>futures/private/order/cancel     </td><td>1 / request</td></tr>
  <tr><td>futures/private/order/cancelAll  </td><td>10 / request</td></tr>
  <tr><td>futures/private/stop-order/cancelAll </td><td>10 / request</td></tr>
  <tr>
    <td rowspan="3">600/min</td>
    <td>futures/private/order/list </td>
    <td>1 / request</td>
  </tr>
  <tr><td>futures/private/stop-order/list </td><td>1 / request</td></tr>
  <tr><td>futures/private/order </td><td>1 / request</td></tr>
  <tr>
    <td>120/min</td>
    <td>futures/private/execution/list</td>
    <td>1 / request</td>
  </tr>
  <tr>
    <td rowspan="5">75/min</td>
    <td>futures/private/position/leverage/save </td>
    <td>1 / request</td>
  </tr>
  <tr><td>futures/private/position/change-position-margin</td><td>1 / request</td></tr>
  <tr><td>futures/private/position/trading-stop</td><td>1 / request</td></tr>
  <tr><td>futures/private/position/switch-mode</td><td>1 / request</td></tr>
  <tr><td>futures/private/position/switch-isolated</td><td>1 / request</td></tr>
  <tr>
    <td rowspan="4">120/min</td> 
  </tr>
  <tr></tr>
  <tr><td>futures/private/position/list</td><td>1 / request</td></tr>
    <tr><td>v2/private/wallet/balance</td><td>1 / request</td></tr>
  <tr>
    <td rowspan="3">120/min</td>
    <tr><td>v2/private/wallet/fund/records</td>
    <td>1 / request</td>
  </tr>
<tr><td>v2/private/wallet/withdraw/list</td><td>1 / request</td></tr>
<tr>
    <td rowspan="2">600/min</td>
    <tr><td>v2/private/account/api-key</td>
    <td>1 / request</td>
  </tr>
</table>

### t(:orderlimits)
t(:rate_para_limits)

### t(:raisemylimit)
t(:rate_para_raise)

### t(:liquidity)
t(:rate_para_liquidity)

#### t(:ofrthreshold)
t(:rate_para_threshold)

##### t(:ofrratio)
t(:rate_para_ratio)

##### t(:ofrratioExample)


<pre class="center-column-nonindent">
t(:rate_pre_ratioExampleA)
</pre>

<pre class="center-column-nonindent">
t(:rate_pre_ratioExampleB)
</pre>


##### t(:ofrminimum)
t(:spot_rate_para_minimum)


#### t(:frequencylimit)
t(:rate_para_frequency)


| t(:column_LCP) | t(:column_frequencyLimit) |
|  ----    | ----  |
| 20-100  | t(:row_frequencyLimit_800) |
| 10-20   | t(:row_frequencyLimit_600) |
| 5-10    | t(:row_frequencyLimit_400) |
| 2-5     | t(:row_frequencyLimit_200) |
| <2      | t(:row_frequencyLimit_100) |

##### t(:liquidityPoints)
t(:rate_para_liquidityPoints)

##### t(:ratelimitsexplanation)
###### t(:pricerange)
t(:rate_para_priceRange)

###### t(:pricerangeExample)
<pre class="center-column-nonindent">
t(:rate_pre_priceRangeExample)
</pre>


###### t(:pou)
t(:rate_para_POU)

<pre class="center-column-nonindent">
t(:rate_pre_POUExample)
</pre>


###### t(:spot_poa)
t(:spot_rate_para_POA)

###### t(:poaExample)
t(:rate_para_POAExample)

<pre class="center-column-nonindent">
t(:rate_pre_POAExample)
</pre>

<aside class="notice">
t(:spot_rate_aside_POAExample)
</aside>
