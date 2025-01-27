# Integration of django with JWT token system 

install -- 

pip install django 

pip install djangorestframework-simplejwt




     REST_FRAMEWORK = {
     
          'DEFAULT_AUTHENTICATION_CLASSES': (
          
              'rest_framework_simplejwt.authentication.JWTAuthentication',
              
         )
         
      }

