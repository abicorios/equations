$0 = \delta S = \delta \int\limits_{t_1}^{t_2} L(q, \dot{q}, t) dt =$

$=\int\limits_{t_1}^{t_2} (\frac{\partial L}{\partial q} \delta q + \frac{\partial L}{\partial \dot{q}} \delta \dot{q}) dt = \int\limits_{t_1}^{t_2} (\frac{\partial L}{\partial q} \delta q + \frac{\partial L}{\partial \dot{q}}\frac{d}{dt}\delta q)dt=$

$=\int\limits_{t_1}^{t_2} (\frac{\partial L}{\partial q} \delta q + \frac{d}{dt} (\frac{\partial L}{\partial \dot{q}} \delta q) - (\frac{d}{dt}\frac{\partial L}{\partial \dot{q}})\delta q)dt =$

$=\int\limits_{t_1}^{t_2} (\frac{d}{dt} (\frac{\partial L}{\partial \dot{q}} \delta q) + \frac{\partial L}{\partial q} \delta q - (\frac{d}{dt}\frac{\partial L}{\partial \dot{q}})\delta q)dt =$

$=\int\limits_{t_1}^{t_2} \frac{d}{dt} (\frac{\partial L}{\partial \dot{q}} \delta q) dt + \int\limits_{t_1}^{t_2} (\frac{\partial L}{\partial q} \delta q - (\frac{d}{dt}\frac{\partial L}{\partial \dot{q}})\delta q)dt =$

$= \int\limits_{t_1}^{t_2} d (\frac{\partial L}{\partial \dot{q}} \delta q) + \int\limits_{t_1}^{t_2} (\frac{\partial L}{\partial q} - (\frac{d}{dt}\frac{\partial L}{\partial \dot{q}}))\delta q dt =$

$= \frac{\partial L}{\partial \dot{q}} \delta q \Big |_{t_1}^{t_2} + \int\limits_{t_1}^{t_2} (\frac{\partial L}{\partial q} - (\frac{d}{dt}\frac{\partial L}{\partial \dot{q}}))\delta q dt $