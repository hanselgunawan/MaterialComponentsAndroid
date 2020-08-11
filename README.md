# Material Components

## Dependency
`api 'com.google.android.material:material:1.1.0-alpha06'`

## TextInputLayout
Layout which wraps a `TextInputEditText`, `EditText`, or descendant to show a floating label when the hint is hidden while the user inputs text.
```
        <com.google.android.material.textfield.TextInputLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_margin="4dp"
            android:hint="@string/shr_hint_username">

            ...

        </com.google.android.material.textfield.TextInputLayout>
```

## TextInputEditText
A special sub-class of `EditText` designed for use as a child of `TextInputLayout`.
```
        <com.google.android.material.textfield.TextInputLayout
            android:id="@+id/password_text_input"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_margin="4dp"
            android:hint="@string/shr_hint_password"
            app:errorEnabled="true">

            <com.google.android.material.textfield.TextInputEditText
                android:id="@+id/password_edit_text"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:inputType="textPassword"/>

        </com.google.android.material.textfield.TextInputLayout>
```

## MaterialButton
A convenience class for creating a new Material button.
```
        <com.google.android.material.button.MaterialButton
            android:id="@+id/next_button"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_alignParentEnd="true"
            android:layout_alignParentRight="true"
            android:text="@string/shr_button_next" />
```

## Demo
<img src="https://imgur.com/GFMFGEv.png" width="450px" height="800px" />
<img src="https://imgur.com/BikJ1bz.png" width="450px" height="800px" />
