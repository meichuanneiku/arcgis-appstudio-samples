## Listed Related Features

This sample demonstrates how to query a layer for features that are in a related table

A Map is constructed by passing a URL to a web map stored in ArcGIS Online. A connection is made to the mouseClicked signal of the MapView, and when this signal emits, selectFeatures is executed on the FeatureLayer. Once this completes, a FeatureQueryResult is returned, giving access to the FeatureIterator. This FeatureIterator contains all of the Feature objects selected with the mouse click. These Feature objects are iterated over, and for each object, the queryRelatedFeatures method is called. Once this completes, the returned RelatedFeatureQueryResult gives access to all of the related features, and the UI is populated with this information.

[Resource Level](https://geonet.esri.com/groups/appstudio/blog/2016/12/06/how-to-describe-our-resources-in-terms-of-difficulty-complexity-and-time-to-digest): 🍌


## Instructions to run this sample in AppStudio Desktop

1. Download the `.zip` file
2. Unzip and copy this folder into AppStudio Apps folder (Windows: `C:\Users\<username>\ArcGIS\AppStudio\Apps` Mac or linux: `Home\ArcGIS\AppStudio\Apps`)
3. The new app will now appear in the AppStudio Desktop. Run the application or open it in the bundled Qt-Creator IDE to look at the code and modify.

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Esri welcomes contributions from anyone and everyone. Please see our [guidelines for contributing](https://github.com/esri/contributing).

## Licensing
Copyright 2017 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](license.txt) file.


[](Esri Tags: ArcGIS Runtime SDK Qt QML JavaScript iOS Android Xamarin Ionic PhoneGap Mac linux Windows Apps samples templates appstudio)
[](Esri Language: Qt QML JavaScript)