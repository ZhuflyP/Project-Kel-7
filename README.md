# Project-Kel-7
Membuat Fragment Booking

<?xml version="1.0" encoding="utf-8"?>
<ScrollView
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="24dp">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <TextView
            android:id="@+id/bookingTitle"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Booking Pemancingan"
            android:textSize="24sp"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/dateLabel"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Select Date"
            android:textSize="16sp"
            android:layout_marginTop="16dp" />

        <TextView
            android:id="@+id/dateTextView"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="dd/mm/yyyy"
            android:textSize="18sp"
            android:padding="16dp"
            android:layout_marginTop="4dp" />

        <Button
            android:id="@+id/pickDateButton"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Pick Date"
            android:layout_marginTop="8dp" />

        <EditText
            android:id="@+id/locationEditText"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Location"
            android:layout_marginTop="16dp"
            android:padding="16dp"
            android:inputType="text" />

        <EditText
            android:id="@+id/notesEditText"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Additional Notes (optional)"
            android:layout_marginTop="8dp"
            android:inputType="textMultiLine"
            android:minLines="3" />

        <Button
            android:id="@+id/bookButton"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Book"
            android:layout_marginTop="24dp" />

        <TextView
            android:id="@+id/bookingStatusTextView"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text=""
            android:textSize="14sp"
            android:layout_marginTop="16dp" />

    </LinearLayout>

</ScrollView>
