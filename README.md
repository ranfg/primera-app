# primera-app
Coursera android course
<?xml version="1.0" encoding="utf-8"?> 
<RelativeLayout 
    xmlns:android="http://schemas.android.com/apk/res/android" 
    xmlns:tools="http://schemas.android.com/tools" 
    android:layout_width="match_parent" 
    android:layout_height="match_parent" 
    android:paddingLeft="@dimen/activity_horizontal_margin" 
    android:paddingRight="@dimen/activity_horizontal_margin" 
    android:paddingTop="@dimen/activity_vertical_margin" 
    android:paddingBottom="@dimen/activity_vertical_margin" 
    tools:context="es.sindicatodelmal.holamundo.MainActivity"> 
 
 
    <ImageView 
        android:layout_width="wrap_content" 
        android:layout_height="wrap_content" 
        android:id="@+id/imageView2" 
        android:src="@drawable/_2fc53db72cf219e20fd61969cbf4461c_marcianito_miprimer_proyecto_android" 
        android:layout_alignParentBottom="true" /> 
 
    <Button 
        android:layout_width="wrap_content" 
        android:layout_height="wrap_content" 
        android:text="@string/Botonentrada" 
        android:id="@+id/button2" 
        android:layout_alignParentTop="true" 
        android:layout_centerHorizontal="true" 
        android:layout_marginTop="159dp" /> 
 
    <TextView 
        android:layout_width="wrap_content" 
        android:layout_height="wrap_content" 
        android:textAppearance="?android:attr/textAppearanceLarge" 
        android:text="Bienvenido" 
        android:id="@+id/textView2" 
        android:textSize="@dimen/abc_action_bar_default_height_material" 
        android:layout_alignParentTop="true" 
        android:layout_centerHorizontal="true" /> 
 
</RelativeLayout> 
