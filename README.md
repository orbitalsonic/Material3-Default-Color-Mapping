# 🧾 Android Material Default Color Mapping

## 🔹 TEXT COMPONENTS

### TextView

| Attribute | Default Color |
|----------|--------------|
| android:textColor | onSurface |
| android:textColorHint | onSurfaceVariant |
| android:textColorLink | primary |
| android:textColorHighlight | secondary |
| android:shadowColor | onSurface (low alpha) |
| android:drawableTint | onSurface |
| android:backgroundTint | surface |
| android:foregroundTint | onSurface |

---

### EditText

| Attribute | Default |
|----------|--------|
| textColor | onSurface |
| textColorHint | onSurfaceVariant |
| textCursorDrawable | primary |
| textSelectHandle* | primary |
| backgroundTint | primary (focused) |
| foregroundTint | onSurface |

**Material Extensions**

| Attribute | Default |
|----------|--------|
| app:cursorColor | primary |
| app:hintTextColor | onSurfaceVariant |

---

### AutoCompleteTextView / MultiAutoCompleteTextView

| Attribute | Default |
|----------|--------|
| textColor | onSurface |
| textColorHint | onSurfaceVariant |
| dropDownBackground | surface |
| popupBackground | surface |

---

### CheckedTextView

| Attribute | Default |
|----------|--------|
| textColor | onSurface |
| checkMarkTint | primary |
| drawableTint | onSurface |

---

### TextInputLayout (Material)

| Attribute | Default |
|----------|--------|
| hintTextColor | onSurfaceVariant |
| boxBackgroundColor | surface |
| boxStrokeColor | outline |
| boxStrokeErrorColor | error |
| startIconTint | onSurfaceVariant |
| endIconTint | onSurfaceVariant |
| passwordToggleTint | onSurfaceVariant |
| counterTextColor | onSurfaceVariant |
| counterOverflowTextColor | error |
| helperTextTextColor | onSurfaceVariant |
| errorTextColor | error |
| placeholderTextColor | onSurfaceVariant |
| prefixTextColor | onSurface |
| suffixTextColor | onSurface |

---

## 🔘 BUTTONS

### Button

| Attribute | Default |
|----------|--------|
| textColor | onPrimary (if filled) |
| backgroundTint | primary |
| foregroundTint | onPrimary |
| drawableTint | onPrimary |

---

### MaterialButton

| Attribute | Default |
|----------|--------|
| backgroundTint | primary |
| rippleColor | onPrimary (alpha) |
| strokeColor | outline |
| iconTint | onPrimary |

---

### ImageButton

| Attribute | Default |
|----------|--------|
| tint | onSurface |
| backgroundTint | surface |
| foregroundTint | onSurface |

---

### Chip

| Attribute | Default |
|----------|--------|
| chipBackgroundColor | surfaceVariant |
| chipStrokeColor | outline |
| rippleColor | onSurface |
| chipIconTint | onSurfaceVariant |
| checkedIconTint | onSecondaryContainer |
| closeIconTint | onSurfaceVariant |
| textColor | onSurfaceVariant |

---

### CheckBox / RadioButton

| Attribute | Default |
|----------|--------|
| buttonTint | primary |
| textColor | onSurface |
| backgroundTint | surface |

---

### ToggleButton

| Attribute | Default |
|----------|--------|
| textColor | onSurface |
| backgroundTint | surfaceVariant |

---

### Switch / SwitchMaterial

| Attribute | Default |
|----------|--------|
| thumbTint | primary |
| trackTint | onSurface (alpha) |
| textColor | onSurface |

---

### FloatingActionButton

| Attribute | Default |
|----------|--------|
| backgroundTint | secondaryContainer |
| rippleColor | onSecondary |
| tint | onSecondaryContainer |

---

## 🧩 WIDGETS

### ImageView

| Attribute | Default |
|----------|--------|
| tint | onSurface |
| backgroundTint | surface |
| foregroundTint | onSurface |

---

### TextClock

| Attribute | Default |
|----------|--------|
| textColor | onSurface |

---

### ProgressBar

| Attribute | Default |
|----------|--------|
| progressTint | primary |
| progressBackgroundTint | surfaceVariant |
| secondaryProgressTint | secondary |
| indeterminateTint | primary |

---

### SeekBar

| Attribute | Default |
|----------|--------|
| thumbTint | primary |
| progressTint | primary |
| progressBackgroundTint | surfaceVariant |
| secondaryProgressTint | secondary |

---

### RatingBar

| Attribute | Default |
|----------|--------|
| progressTint | primary |
| secondaryProgressTint | surfaceVariant |
| progressBackgroundTint | surfaceVariant |

---

### SearchView

| Attribute | Default |
|----------|--------|
| textColor | onSurface |
| textColorHint | onSurfaceVariant |
| backgroundTint | surface |
| foregroundTint | onSurface |

---

### TextureView

| Attribute | Default |
|----------|--------|
| - | No default color roles (content-driven rendering) |

---

## 🧱 CONTAINERS

### AppBarLayout

| Attribute | Default |
|----------|--------|
| background | surface |
| backgroundTint | surface |

---

### Toolbar

| Attribute | Default |
|----------|--------|
| titleTextColor | onSurface |
| subtitleTextColor | onSurfaceVariant |
| background | surface |
| navigationIconTint | onSurface |
| logoTint | onSurface |

---

### NavigationView

| Attribute | Default |
|----------|--------|
| itemIconTint | onSurfaceVariant |
| itemTextColor | onSurface |
| itemBackground | secondaryContainer |

---

### Spinner

| Attribute | Default |
|----------|--------|
| popupBackground | surface |
| backgroundTint | surfaceVariant |

---

### CardView / MaterialCardView

| Attribute | Default |
|----------|--------|
| cardBackgroundColor | surface |
| cardForegroundColor | onSurface |
| strokeColor | outline |
| rippleColor | onSurface |

---

## 📦 OTHERS

### Dialog / BottomSheet

| Attribute | Default |
|----------|--------|
| background | surface |
| backgroundTint | surface |

---

### CalendarView

| Attribute | Default |
|----------|--------|
| focusedMonthDateColor | onSurface |
| unfocusedMonthDateColor | onSurfaceVariant |
| weekNumberColor | onSurfaceVariant |
| selectedWeekBackgroundColor | primary |

---

### TimePicker

| Attribute | Default |
|----------|--------|
| headerTextColor | primary |
| textColor | onSurface |
