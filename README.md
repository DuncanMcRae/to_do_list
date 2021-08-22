# to_do_list
Programming to do list


# MEAN AS DEPTH DRIVER
  Include an output with warnings of sensors not coming in. In the worker create a list of dequeues with maxlen=10. Then, at the end of the calcs, add the sensor data to the deque. Check to see if all the incoming data, stacked in the deque is the same. Something like":
    * any(data = data.mean() for data in sensors)   <<< check all data against the mean and if they are the same they will result True. If any are True...then new data is not coming in.


# S-LOG DECODER
# USBL CALIBRATION
# R/T TIDES
# VORF CREATOR
# WEB APPS
  Have a web-app server offshore (RPi?) that can be accessed over the network. The web-apps could be output on different ports. Check out Streamlit for a simple web-app generation. Otherwise, flask or django. Dashboards for none user-input data using something like Streamlit or dash.
  https://towardsdatascience.com/coding-ml-tools-like-you-code-ml-models-ddba3357eace
  


#
