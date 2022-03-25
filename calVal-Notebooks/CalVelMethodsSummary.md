As described below this process amounts to comparing L3 velocity products generated as described in the NISAR ATBD with points of known velocity and elevations. Specifically, the Cal/Val points will consist of:
* Zero velocity points on exposed bedrock; and
* On-ice GPS measurements of ice flow speed ($v_x$,$v_y$) and elevation ($z$).

Errors are evaluated as the means ($\mu_x,\mu_y$), standard deviations ($\sigma_x,\sigma_y$), and root-mean-squares (rms) of the diferences between the SAR-measured velocity ($v_x,v_y$) and the nominally GPS-measured cal/val points ($u_x,u_y$). Explicitly, these calculations are:

$\bar{\mu}_x = \frac{1}{N_{pts}}\sum \limits_{i=1}^{N_{pts}} (v_x-u_x)$, &nbsp;&nbsp;&nbsp;       $\bar{\mu}_y = \frac{1}{N_{pts}}\sum \limits_{i=1}^{N_{pts}} (v_x-u_x)$ </br>
$\hat{\sigma}_x^2 = \frac{1}{N_{pts}-1}\sum \limits_{i=1}^{N_{pts}} ((v_x-u_x)-\bar{\mu_x})^2$, &nbsp;&nbsp;&nbsp;    $\hat{\sigma}_y^2 = \frac{1}{N_{pts}-1}\sum \limits_{i=1}^{N_{pts}} ((v_y-u_y)-\bar{\mu_y})^2$ </br>
$rms_x = \sqrt{\frac{1}{N_{pts}}\sum \limits_{i=1}^{N_{pts}} ((v_x-u_x))^2}$, &nbsp;&nbsp;&nbsp; 
$rms_y = \sqrt{\frac{1}{N_{pts}}\sum \limits_{i=1}^{N_{pts}} ((v_y-u_y))^2}$

The requirement poses the error in terms of a fixed value (1 m/yr) and percentage error (3%). To pass the requirement for a set of points, the mean error of the results should be less than the mean error thresholds for the point. Conceptually, if not rigorously, these two error sources can be thought of as the precision component (1 m/yr) and potential bias (3%). Consistent biases at a point through time may be caused by processing artifacts such as a slope error in the DEM used to apply the surface parallel flow correction. Specifically, the error should be less than:

${thresh}_x = \sqrt{\frac{1}{N_{pts}}\sum \limits_{i=1}^{N_{pts}} (1)^2 + (0.03u_x)^2 }$ m/yr, &nbsp;&nbsp;&nbsp;    ${thresh}_y = \sqrt{\frac{1}{N_{pts}}\sum \limits_{i=1}^{N_{pts}} (1)^2 + (0.03u_y)^2 }$ m/yr

Since biases are possible, the requirement is met where the $rms$ for a component is less the than corresponding $thresh$.