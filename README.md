# Aplicacion Bienvenido
Just another repository

//Vista Portrait

<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/marciano"
    android:scrollbarThumbHorizontal="@drawable/marciano"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginEnd="156dp"
        android:layout_marginRight="156dp"
        android:layout_marginBottom="342dp"
        android:text="@string/boton"
        android:textColor="@android:color/background_dark"
        android:textSize="20sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginEnd="59dp"
        android:layout_marginRight="59dp"
        android:layout_marginBottom="175dp"
        android:text="@string/intro"
        android:textColor="#FFFFFF"
        android:textColorLink="#FFFFFF"
        android:textSize="60sp"
        app:layout_constraintBottom_toTopOf="@+id/button"
        app:layout_constraintEnd_toEndOf="parent" />
</android.support.constraint.ConstraintLayout>

                                                                                         VISTAS
\\Vista Landscape


<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/marciano"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="62dp"
        android:layout_marginEnd="322dp"
        android:layout_marginRight="322dp"
        android:text="@string/boton"
        android:textColor="@android:color/background_dark"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="6dp"
        android:layout_marginEnd="219dp"
        android:layout_marginRight="219dp"
        android:text="@string/intro"
        android:textColor="#FFFFFF"
        android:textColorLink="#FFFFFF"
        android:textSize="60sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
</android.support.constraint.ConstraintLayout>


\\Vista Tablet Portrait



<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/marciano"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/button"
        android:layout_width="184dp"
        android:layout_height="81dp"
        android:layout_marginTop="237dp"
        android:layout_marginEnd="210dp"
        android:layout_marginRight="210dp"
        android:text="@string/boton"
        android:textColor="@android:color/background_dark"
        android:textSize="30sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="97dp"
        android:layout_marginEnd="104dp"
        android:layout_marginRight="104dp"
        android:text="@string/intro"
        android:textColor="#FFFFFF"
        android:textColorLink="#FFFFFF"
        android:textSize="80sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
</android.support.constraint.ConstraintLayout>


\\Vista Tablet Landscape


<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/marciano"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/button"
        android:layout_width="123dp"
        android:layout_height="73dp"
        android:layout_marginTop="25dp"
        android:layout_marginEnd="304dp"
        android:layout_marginRight="304dp"
        android:text="@string/boton"
        android:textColor="@android:color/background_dark"
        android:textSize="20sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="7dp"
        android:layout_marginEnd="170dp"
        android:layout_marginRight="170dp"
        android:text="@string/intro"
        android:textColor="#FFFFFF"
        android:textColorLink="#FFFFFF"
        android:textSize="80sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
</android.support.constraint.ConstraintLayout>


\\Vista Television 

<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/marciano"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="62dp"
        android:layout_marginEnd="322dp"
        android:layout_marginRight="322dp"
        android:text="@string/boton"
        android:textColor="@android:color/background_dark"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="6dp"
        android:layout_marginEnd="219dp"
        android:layout_marginRight="219dp"
        android:text="@string/intro"
        android:textColor="#FFFFFF"
        android:textColorLink="#FFFFFF"
        android:textSize="60sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
</android.support.constraint.ConstraintLayout>

                                                                                STRINGS
                                                                                
\\Por default Español
<resources>
    <string name="app_name">MiApplicación</string>
    <string name="boton">Entrar</string>
    <string name="intro">Bienvenido</string>
</resources>

\\Ingles
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="app_name">MyAplicación</string>
    <string name="boton">Enter</string>
    <string name="intro">Welcome</string>
</resources>

\\Frances 
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="app_name">MonApplication</string>
    <string name="boton">Entrer</string>
    <string name="intro">Bienvenue</string>
</resources>

\\Aleman
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="app_name">MeineApp</string>
    <string name="boton">Eingeben</string>
    <string name="intro">Willkommen</string>
</resources>
