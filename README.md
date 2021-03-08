# Leopard_data
Data from LAGO WCD detector
Data fdormat as follows

# v 5
# #
# # This is a LAGO raw data file, version 5
# # It contains the following data:
# #   <N1> <N2> <N3>   : line with values of the 3 ADC for a triggered pulse
# #   # t <C> <V>      : end of a trigger
# #                      gives the channel trigger (<C>: 3 bit mask) and 40MHZ clock count (<V>) of the trigger time
# #   # c <C>          : internal trigger counter
# #   # x f <V>        : 40 MHz frequency
# #   # x r C1-DD <V>  : raw temperature and pressure sensor value
# #   # x r D1 <V>     : raw temperature/pressure value
# #   # x r D2 <V>     : raw temperature/pressure value
# #   # x h <HH:MM:SS> <DD/MM/YYYY> <S> : GPS time (every new second, last number is seconds since EPOCH)
# #   # x s <T> C <P> hPa <A> m : temperature <T>, pressure <P> and altitude (from pressure) <A>
# #   # x g <LAT> <LON> <ALT>   : GPS data - latitude, longitude, altitude
# #   # x b <B1> <B2> <B3>      : baselines (NOT IMPLEMENTED IN LAGO)
# # In case of error, an unfinished line will be finished by # E @@@
# # Followed by a line with # E <N> and the error message in human readable format, where <N> is the error code:
# #   # E 1 : read timeout of 2 seconds
# #   # E 2 : too many buffer reading tries
# #   # E 3 : unknown word from FPGA
