# PyCharm Django Snippets

**PyCharm live templates** support for `Django 1.10`. This effort is heavily inspired by [Djaneiro](https://github.com/squ1b3r/Djaneiro) which I use when I was still a Sublime Text user.

## Installation

Copy XML file to templates folder in the following locations:

* Windows: `<your home directory>\.<product name><version number>\config\templates`
* Linux: `~/.<product name><version number>/config/templates`
* OSX: `~/Library/Preferences/<product name><version number>/templates`

## Template Tags

![](template-demo.gif)

- [x] **variable** - `{{ }}`
- [x] **autoescape** - `{% autoescape %} {% autoescape %}`
- [x] **block** - `{% block %} {% endblock %}`
- [x] **comment** - `{% comment %} {% endcomment %}`
- [x] **csrf** - `{% csrf_token %}`
- [x] **cycle** - `{% cycle %}`
- [x] **debug** - `{% debug %}`
- [x] **ext** - `{% extends "" %}`
- [x] **extends** - `{% extends "" %}`
- [x] **filter** - `{% filter %} {% endfilter %}`
- [x] **firstof** - `{% firstof %}`
- [x] **for** - `{% for in %} {% endfor %}`
- [x] **fore** - `{% for in %} {% empty %} {% endfor %}`
- [x] **if** - `{% if %} {% endif %}`
- [x] **else** - `{% else %}`
- [x] **elif** - `{% elif %}`
- [x] **ife** - `{% if %} {% else %} {% endif %}`
- [x] **ifelse** - `{% if %} {% else %} {% endif %}`
- [x] **ifchanged** - `{% ifchanged %} {% endifchanged %}`
- [x] **inc** - `{% include %}`
- [x] **include** - `{% include %}`
- [x] **load** - `{% load %}`
- [x] **lorem** - `{% lorem [count] [method] [random] %}`
- [x] **now** - `{% now "" %}`
- [x] **regroup** - `{% regroup by as %}`
- [x] **spaceless** - `{% spaceless %} {% endspaceless %}`
- [x] **static** - `{% static %}`
- [x] **url** - `{% url %}`
- [x] **verbatim** - `{% verbatim %} {% endverbatim %}`
- [x] **widthratio** - `{% widthratio %}`
- [x] **with** - `{% with as %} {% endwith %}`
- [x] **trans** - `{% trans %}`
- [x] **blocktrans** - `{% blocktrans with as %} {% endblocktrans %}`
- [x] **i18n** - `{% load i18n %}`
- [x] **l10n** - `{% load l10n %}`
- [x] **tz** - `{% load tz %}`

## Python Code

### Model Fields

- [x] **mauto** - `models.AutoField`
- [x] **mbigauto** - `models.BigAutoField`
- [x] **mbigint** - `models.BigIntegerField`
- [x] **mbin** - `models.BinaryField`
- [x] **mbool** - `models.BooleanField`
- [x] **mchar** - `models.CharField`
- [x] **mcomma** - `models.CommaSeparatedIntegerField`
- [x] **mdate** - `models.DateField`
- [x] **mdatetime** - `models.DateTimeField`
- [x] **mdecimal** - `models.DecimalField`
- [x] **mduration** - `models.DurationField`
- [x] **memail** - `models.EmailField`
- [x] **mfile** - `models.FileField`
- [x] **mfilepath** - `models.FilePathField`
- [x] **mfloat** - `models.FloatField`
- [x] **mimage** - `models.ImageField`
- [x] **mint** - `models.IntegerField`
- [x] **mip** - `models.GenericIPAddressField`
- [x] **mnullbool** - `models.NullBooleanField`
- [x] **mposint** - `models.PositiveIntegerField`
- [x] **mpossmallint** - `models.PositiveSmallIntegerField`
- [x] **mslug** - `models.SlugField`
- [x] **msmallint** - `models.SmallIntegerField`
- [x] **mtext** - `models.TextField`
- [x] **mtime** - `models.TimeField`
- [x] **murl** - `models.URLField`
- [x] **muuid** - `models.UUIDField`
- [x] **fk** - `models.ForeignKey`
- [x] **m2m** - `models.ManyToManyField`
- [x] **o2o** - `models.OneToOneField`

### PostgreSQL-Specific Model Fields

- [x] **marray** - `ArrayField`
- [x] **mhstore** - `HStoreField`
- [x] **mjson** - `JSONField`
- [x] **mintrange** - `IntegerRangeField`
- [x] **mbigintrange** - `BigIntegerRangeField`
- [x] **mfloatrange** - `FloatRangeField`
- [x] **mdatetimerange** - `DateTimeRangeField`
- [x] **mdaterange** - `DateRangeField`

### Tests

- [x] **testcase** - generic test function with `Given`, `When`, `Then` comment sections
- [x] **testmodel** - functions for testing `create`, `update` and `delete`
- [x] **testview** - functions for testing `view_success`, `view_failure`, `create_success`, `create_failure`, `update_success`, `update_failure`, `delete_success`, `delete_failure``
- [ ] **testform** - 


```python
def test_case(self, client):
    # Given: 
    # When:
    # Then:
    assert 1 == 2
```

```python
class TestModel:

    def test_create(self):
        # Given: 
        # When:
        # Then:
        assert 1 == 2

    def test_update(self):
        # Given: 
        # When:
        # Then:
        assert 1 == 2

    def test_delete(self):
        # Given: 
        # When:
        # Then:
        assert 1 == 2
```

```python
class TestView:

    def test_view_success(self):
        # Given: 
        # When:
        # Then:
        assert 1 == 2

    def test_view_failure(self):
        # Given: 
        # When:
        # Then:
        assert 1 == 2

    def test_create_success(self):
        # Given: 
        # When:
        # Then:
        assert 1 == 2

    def test_create_failure(self):
        # Given: 
        # When:
        # Then:
        assert 1 == 2

    def test_update_success(self):
        # Given: 
        # When:
        # Then:
        assert 1 == 2

    def test_update_failure(self):
        # Given: 
        # When:
        # Then:
        assert 1 == 2

    def test_delete_success(self):
        # Given: 
        # When:
        # Then:
        assert 1 == 2

    def test_delete_failure(self):
        # Given: 
        # When:
        # Then:
        assert 1 == 2
```
