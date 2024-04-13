
# Rapport

**Skriv din rapport här!**

_Du kan ta bort all text som finns sedan tidigare_.

## Följande grundsyn gäller dugga-svar:

- As seen inb the following code, waht i did was that firstlly i added three diffrent widgeds, 
- being a textview, button, and a switch. then i added constriants for each one of them so that they 
- would apper in a ordely maner by adding layout_constraint such as the bottom of the above widget.
- on button i allso added a match parrent width, and a margin constraint that it would apeer 100
- dp from each side. i have also inclueded a linearview with a vertical orientation to wholed all of
- the widgets, but when i added it, all of the elements went to the top, which i am unsure why that 
- ouccered.
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    ...>

    <LinearLayout

        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical">


            <TextView
                android:id="@+id/text"
                ... />

            <Button
                android:id="@+id/button"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="asdasdasdasdasdasdasd"
                app:layout_constraintBottom_toTopOf="@id/switch1"
                app:layout_constraintLeft_toLeftOf="parent"
                app:layout_constraintRight_toRightOf="parent"
                app:layout_constraintTop_toBottomOf="@id/text"

                android:layout_marginEnd="100dp"
                android:layout_marginStart="100dp" />

            <Switch
                android:id="@+id/switch1"
                .../>


    </LinearLayout>
</androidx.constraintlayout.widget.ConstraintLayout>
```

Bilder läggs i samma mapp som markdown-filen.

![](android2.png)

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
