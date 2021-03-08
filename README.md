# Leopard_data
Data from LAGO WCD detector

Data format as follows

Each column correspond to 1 input channel (Only 2 channels are used)

Baseline to each channel set to 50

1st Channel (CH0) is PMT amplified output

2nd Channel (CH1) is last dynode output

Each pulse is acquired in 12 bins at 40MHz rate (25ns time resolution)


 t 1 50083  // Trigger info channel number  time stamp
 
 c 3012     //  Pulse counter
 
51 49 49    //  CH0 CH1  CH2 output

51 50 49

68 53 51

61 48 50

51 49 49

51 51 50

53 48 49

57 48 50

53 50 49

51 48 50

50 49 48

50 50 49

