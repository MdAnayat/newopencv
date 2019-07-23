cv::Mat rot_mat = getRotationMatrix2D(cv::Point2f(center,angle,scale);
Calculates an affine matrix of 2D rotation.
center:	Center of the rotation in the source image.
angle:	Rotation angle in degrees. Positive values mean counter-clockwise rotation (the coordinate origin is assumed to be the top-left corner).
scale:	Isotropic scale factor.
