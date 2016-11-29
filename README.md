# PyCharm Django Snippets

**PyCharm live templates** support for `Django 1.10`. This effort is heavily inspired by [Djaneiro](https://github.com/squ1b3r/Djaneiro) which I use when I was still a Sublime Text user.

## Template Tags

- [x] `autoescape` - {% autoescape %} {% autoescape %}
- [x] `block` - {% block %} {% endblock %}
- [x] `comment` - {% comment %} {% endcomment %}
- [x] `csrf` - {% csrf_token %}
- [x] `cycle` - {% cycle %}
- [x] `debug` - {% debug %}
- [x] `ext` - {% extends "" %}
- [x] `extends` - {% extends "" %}
- [x] `filter` - {% filter %} {% endfilter %}
- [x] `firstof` - {% firstof %}
- [x] `for` - {% for in %} {% endfor %}
- [x] `fore` - {% for in %} {% empty %} {% endfor %}
- [x] `if` - {% if %} {% endif %}
- [x] `else` - {% else %}
- [x] `elif` - {% elif %}
- [x] `ife` - {% if %} {% else %} {% endif %}
- [x] `ifelse` - {% if %} {% else %} {% endif %}
- [x] `ifchanged` - {% ifchanged %} {% endifchanged %}
- [x] `inc` - {% include %}
- [x] `include` - {% include %}
- [x] `load` - {% load %}
- [x] `lorem` - {% lorem [count] [method] [random] %}
- [x] `now` - {% now "" %}
- [x] `regroup` - {% regroup by as %}
- [x] `spaceless` - {% spaceless %} {% endspaceless %}
- [x] `static` - {% static %}
- [x] `url` - {% url %}
- [x] `verbatim` - {% verbatim %} {% endverbatim %}
- [x] `widthratio` - {% widthratio %}
- [x] `with` - {% with as %} {% endwith %}
- [x] `trans` - {% trans %}
- [x] `blocktrans` - {% blocktrans with as %} {% endblocktrans %}
- [x] `i18n` - {% load i18n %}
- [x] `l10n` - {% load l10n %}
- [x] `tz` - {% load tz %}

## Python Code

### Model Fields

- [ ] `mauto` - AutoField
- [ ] `mbigauto` - BigAutoField
- [ ] `mbigint` - BigIntegerField
- [ ] `mbin` - BinaryField
- [ ] `mbool` - BooleanField
- [ ] `mchar` - CharField
- [ ] `mcomma` - CommaSeparatedIntegerField
- [ ] `mdate` - DateField
- [ ] `mdatetime` - DateTimeField
- [ ] `mdecimal` - DecimalField
- [ ] `mduration` - DurationField
- [ ] `memail` - EmailField
- [ ] `mfile` - FileField
- [ ] `mfilepath` - FilePathField
- [ ] `mfloat` - FloatField
- [ ] `mimage` - ImageField
- [ ] `mint` - IntegerField
- [ ] `mip` - GenericIPAddressField
- [ ] `mnullbool` - NullBooleanField
- [ ] `mposint` - PositiveIntegerField
- [ ] `mpossmallint` - PositiveSmallIntegerField
- [ ] `mslug` - SlugField
- [ ] `msmallint` - SmallIntegerField
- [ ] `mtext` - TextField
- [ ] `mtime` - TimeField
- [ ] `murl` - URLField
- [ ] `muuid` - UUIDField
- [ ] `fk` - ForeignKey
- [ ] `m2m` - ManyToManyField
- [ ] `o2o` - OneToOneField

### PostgreSQL-Specific Model Fields 
- [ ] `marray` - ArrayField
- [ ] `mhstore` - HStoreField
- [ ] `mjson` - JSONField
- [ ] `mintrange` - IntegerRangeField
- [ ] `mbigintrange` - BigIntegerRangeField
- [ ] `mfloatrange` - FloatRangeField
- [ ] `mdatetimerange` - DateTimeRangeField
- [ ] `mdaterange` - DateRangeField

### Miscellaneous

- [ ] `testcase` - generic function with `Given`, `When`, `Then` comment sections
- [ ] `testmodel` - functions for testing `create`, `update` and `delete`
- [ ] `testview` - functions for testing `view_success`, `view_failure`, `create_success`, `create_failure`, `update_success`, `update_failure`, `delete_success`, `delete_failure`
- [ ] `testform` - 