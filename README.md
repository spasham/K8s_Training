# K8s_Training

Set-based vs Equity-based selectors:

**Equity-based selectors allow filtering by label key and values. So, in layman terms, the equity-based selector will only look for the pods which will have the exact same phrase as that of the label.
Suppose your label key says app=nginx, then, with this selector, you can only look for those pods with label app equal to nginx.

**This type of selector allows filtering keys according to a set of values. So, in other words, the selector based selector will look for pods whose label has been mentioned in the set.
Say your label key says app in (nginx, NPS, Apache). Then, with this selector, if your app is equal to any of nginx, NPS, or Apache, then the selector will take it as a true result.
