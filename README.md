This toolkit (Airflow Analytical Toolkit) serves for airflow ananlysis in built environment, including a velocity characteristic analytical toolkit and a direction characteristic analytical toolkit.
It can do the following analyses:
1. Basic but critical parameters of an airflow (velocity, turbulence)
2. Power spectral analysis
3. Wavelet analysis
4. Chaos analysis
5. Auto-correlation analysis
6. Weibull distribution analysis
7. Component velocities analysis
8. Graphic demonstration
   
Before use:
✔ Before using this program, it is not necessary to install MATLAB, but the MCR compiler must be installed! You can download the file at this address:
https://www.mathworks.com/products/compiler/matlab-runtime.html
✔ Attached files (templates) are the templates for data importing.

Introduction for this toolkit:
✔ The Airflow Analytical Toolkit (AAT) includes a velocity analytical toolbox and a direction analytical toolbox. The velocity toolkit supports four types of data import methods: Swema03 hot ball anemometer <two formats>, RM YOUNG 81000 ultrasonic anemometer, and a generic format, while the direction analytical toolbox currently supports the sample collected by RM YOUNG 81000 only. We suggest the required sampling frequency of the airflow measurement should be more than 10 Hz, the minimum sampling duration should be 409.5 s (when f=10 Hz) at least.
✔ For airflow measurement, the following paper can be referred:
Xie, Z., Xie, Y., Cao, B., & Zhu, Y. (2023). A study of the characteristics of dynamic incoming flow directions of different airflows and their influence on wind comfort. Building and Environment, 110861. https://doi.org/10.1016/j.buildenv.2023.110861
Ouyang, Q. et al., (2006). Study on dynamic characteristics of natural and mechanical wind in built environment using spectral analysis. Building and Environment, 41(4), pp.418–426.
✔ Data import-calculation-export (Velocity box as an example):
Import → Click to time series plot → Basic parameters calculation → Spectrum analysis → Chaos analysis → Wavelet transform → Other parameters → Export (Note: Calculating relevant dimensions takes about 3 to 5 minutes. It is recommended to calculate at the end or only for specific analyses)
✔ Unfortunately, the current toolkit has limited support for sample types collected by different airflow measurements. If you are using a various anemometer, you can import data using a <generic format> file. In addition, the wind direction tool currently only supports RM 81000 ultrasonic sample import. We will expand the sample library of the toolbox in the future.
✔ If you have any questions, please feel free to ask!
email-address: Zuoyu Xie, xiezy21@mails.tsinghua.edu.
