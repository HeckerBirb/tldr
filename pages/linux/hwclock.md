# hwclock

> Read or change the hardware clock. Usually requires root.
> More information: <https://manned.org/hwclock>.

- Display the current time as reported by the hardware clock:

`hwclock`

- Write the current software clock time to the hardware clock (sometimes used during system setup):

`hwclock {{[-w|--systohc]}}`

- Write the current hardware clock time to the software clock:

`hwclock {{[-s|--hctosys]}}`
