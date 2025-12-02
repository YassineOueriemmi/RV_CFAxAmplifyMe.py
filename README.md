# RV_CFAxAmplifyMe.py
A Python/Tkinter tool that calculates long/short quantities based on price inputs, base notional, and target net exposure.

This tool helps quickly compute:
Long & short notionals
Long & short quantities
Custom net exposure (0 → 500k)
Relative-value position sizing based on two asset prices

It is designed for quick usage and training practice (AmplifyME, CFA, trading games, etc.).

Functionality

Given:
Long ticker price
Short ticker price
Base notional
Target net exposure

The calculator computes:
Long notional = Base + Net/2
Short notional = Base − Net/2
Long quantity = Long notional / Price A
Short quantity = Short notional / Price B
