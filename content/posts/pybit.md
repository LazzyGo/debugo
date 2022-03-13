---
title: "Pybit API"
date: 2022-03-07T12:25:48Z
tags: ["pybit"]
categories: ["python"]
---

## Market Data Endpoints

 - query_kline
 - last_information_for_symbol
 - public_trading_records
 - get_the_last_funding_rate
 - query_mark_price_kline
 - query_index_price_kline
 - query_premium_index_kline

## Account Data Endpoints

### active order
 - place_active_order
 - get_active_order
 - cancel_active_order
 - cancel_all_active_orders
 - replace_active_order
 - query_active_order

### conditional order
 - place_conditional_order
 - get_conditional_order
 - cancel_conditional_order
 - cancel_all_conditional_orders
 - replace_conditional_order
 - query_conditional_order

### position
 - my_position
 - set_auto_add_margin
 - cross_isolated_margin_switch
 - position_mode_switch
 - add_reduce_margin
 - set_leverage
 - set_trading_stop
 - user_trade_records
 - closed_profit_and_loss

## Wallet Data Endpoints

 - get_wallet_balance
 - wallet_fund_records
 - withdraw_records
 - asset_exchange_records

## API Data Endpionts

 - server_time
