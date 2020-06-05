# naitingFM
音乐播放器
<co.mobiwise.library.MusicPlayerView
        android:id="@+id/mpv"
        android:layout_width="250dp"
        android:layout_height="250dp"
        app:buttonColor="#FF0028"
        app:cover="@drawable/IMG_bofangqi"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:progressEmptyColor="#20FFFFFF"
        app:progressLoadedColor="#00815E"
        app:textColor="#80FFFFFF"
        app:textSize="14sp" />

    <LinearLayout
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintTop_toTopOf="@id/mpv"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent">

        <ImageView
            android:id="@+id/imageView5"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            app:srcCompat="@drawable/ic_skip_previous_black_24dp" />

        <ImageView
            android:id="@+id/imageView7"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            app:srcCompat="@drawable/ic_favorite_black_24dp" />

        <ImageView
            android:id="@+id/imageView8"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            app:srcCompat="@drawable/ic_skip_next_black_24dp" />

    </LinearLayout>
