
# Android Fingerprint Manager
Fingerprint Manager is the class used to access the Fingerprint hardware from the device.
Google recommends authenticating fingerprint in applications by displaying a DialogFragment with a Fingerprint icon to the user.


## Lets start

###Step:1
We need permission to authendicate user finger access. So  in your Andriod Manifeast.xml add
> android.permission.USE_FINGERPRINT"

###Step:2
Check the device has fingerprint access 

>mFingerprintManager.isHardwareDetected()&& mFingerprintManager.hasEnrolledFingerprints();

the above code will returns the boolean about the access. 
                
                
