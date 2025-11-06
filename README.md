# InventoryVoic<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="16dp">

    <TextView
        android:id="@+id/tvStatus"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:text="آماده شنیدن..."
        android:textSize="18sp"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"/>

    <Button
        android:id="@+id/btnSpeak"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="🎤 بگو"
        app:layout_constraintTop_toBottomOf="@id/tvStatus"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginTop="24dp"/>

    <Button
        android:id="@+id/btnList"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="لیست موجودی"
        app:layout_constraintTop_toBottomOf="@id/tvStatus"
        app:layout_constraintEnd_toEndOf="parent"
        android:layout_marginTop="24dp"/>

    <TextView
        android:id="@+id/tvInventory"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:layout_marginTop="24dp"
        android:text="لیست کالاها اینجا نمایش داده می‌شود."
        app:layout_constraintTop_toBottomOf="@+id/btnSpeak"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintBottom_toBottomOf="parent"/>

</androidx.constraintlayout.widget.ConstraintLayout>
