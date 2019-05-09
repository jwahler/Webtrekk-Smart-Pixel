<a name="1.0.4"></a>
## 1.0.4 (2019-xx-xx)

### Bug Fixes

* Support comma in page name

### Features

* Deactivate CDB for Safari (ITP 2.1)

### Performance Improvements

* Optimize extension tracking
* Write request queue instantly

<a name="1.0.3"></a>
## 1.0.3 (2019-04-02)

### Features

* Integrate 'submit' to change the internal form status to 'submitted' ([Form](https://docs.webtrekk.com/display/WSP/wtSmart.extension.form))

## Security Improvements

* Send every request via SSL

<a name="1.0.2"></a>
## 1.0.2 (2019-02-27)

### Bug Fixes

* Use fallback page name if this is empty

### Features

* Add website goals to actions ([Action](https://docs.webtrekk.com/display/WSP/wtSmart.action))
* Support an array of TrackIds ([Init](https://docs.webtrekk.com/display/WSP/wtSmart.init))

### Performance Improvements

* Send only tracking parameter that differ from the default value
* Remove not supported tracking parameter

<a name="1.0.1"></a>
## 1.0.1 (2019-01-10)

### Features

* Integrate 'update' for manually page changes (Product-List-Tracking) ([Product-List-Tracking](https://docs.webtrekk.com/display/WSP/wtSmart.extension.product_list_tracking))
* Integrate 'reload' for manually page changes (Teaser-Tracking) ([Teaser-Tracking](https://docs.webtrekk.com/display/WSP/wtSmart.extension.teaser_tracking))
* Integrate 'trackPage' and 'trackAction' to force page and action requests ([track](https://docs.webtrekk.com/display/WSP/wtSmart.track))
* Integrate offline tracking ([requestQueue](https://docs.webtrekk.com/display/WSP/wtSmart.advanced))
* Enable and disable developer mode ([Debug](https://docs.webtrekk.com/display/WSP/Integrating+the+Smart+Pixel))
* Use existing old EverID ([forceOldEverId](https://docs.webtrekk.com/display/WSP/wtSmart.advanced))
* Possibility to remove individual properties

### Extensions

* Extension for Product-List-Tracking ([Product-List-Tracking](https://docs.webtrekk.com/display/WSP/wtSmart.extension.product_list_tracking))
* Extension for CDB-IDd ([CDB](https://docs.webtrekk.com/display/WSP/wtSmart.extension.cdb))
* Extension for MediaTracking ([Media](https://docs.webtrekk.com/display/WSP/wtSmart.extension.media))

<a name="1.0.0"></a>
## 1.0.0 (2018-08-08)

* Alpha release