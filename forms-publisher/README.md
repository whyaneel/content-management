# Register DCTs

Categories, Data Capture Templates should be registered in **templating.cfg**

Whatever DCTs implemented in this forms-publisher are already added in **setup\templating.cfg**

````
copy setup\templating.cfg to `iwgethome`\local\config\
````
or

add the entries, for a category **basics** and dct **browser** syntax is as follows.
````
<category name="basics">
    <locations>
        <branch vpath-regex="*.*"/>
    </locations>
    <data-type name="browser" dcr-type="xml">
    </data-type>
</category>
````