# ErrFood

## Overview

This plugin is a eating food reminder and a random restaurant picker

## Configuration

Trigger food_time_call function at 11:30 and return the result in the channel @mix-squad
```
!plugin config Food ['30 11 * * * .food_time_call @mix-squad']
```

## Usage

Choose a restaurant: `!food-pick`