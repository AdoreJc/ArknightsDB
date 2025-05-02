# Component

**Namespace:** `UnityEngine`


## Properties

- `Transform transform`

- `GameObject gameObject`

- `String tag`


## Methods

- `Transform get_transform()`

- `GameObject get_gameObject()`

- `Component GetComponent(Type)`

- `T GetComponent()`

- `Boolean TryGetComponent(Type, out)`

- `Boolean TryGetComponent(out)`

- `Component GetComponent(String)`

- `Component GetComponentInChildren(Type, Boolean)`

- `Component GetComponentInChildren(Type)`

- `T GetComponentInChildren(Boolean)`

- `T GetComponentInChildren()`

- `Void GetComponentsInChildren(Boolean, List`1)`

- `Void GetComponentsInChildren(List`1)`

- `Component GetComponentInParent(Type, Boolean)`

- `Component GetComponentInParent(Type)`

- `T GetComponentInParent(Boolean)`

- `T GetComponentInParent()`

- `Void GetComponentsInParent(Boolean, List`1)`

- `Void GetComponentsForListInternal(Type, Object)`

- `Void GetComponents(Type, List`1)`

- `Void GetComponents(List`1)`

- `String get_tag()`

- `Void set_tag(String)`

- `Boolean CompareTag(String)`

- `Void SendMessageUpwards(String, Object, SendMessageOptions)`

- `Void SendMessageUpwards(String, Object)`

- `Void SendMessageUpwards(String)`

- `Void SendMessageUpwards(String, SendMessageOptions)`

- `Void SendMessage(String, Object)`

- `Void SendMessage(String)`

- `Void SendMessage(String, Object, SendMessageOptions)`

- `Void SendMessage(String, SendMessageOptions)`

- `Void BroadcastMessage(String, Object, SendMessageOptions)`

- `Void BroadcastMessage(String, Object)`

- `Void BroadcastMessage(String)`

- `Void BroadcastMessage(String, SendMessageOptions)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Component : Object
{

	public Transform transform { get; }
	public GameObject gameObject { get; }
	public String tag { get; set; }

	// RVA: 0x6883154 VA: 0x7598e9b154
	public Transform get_transform() { }
	// RVA: 0x6883190 VA: 0x7598e9b190
	public GameObject get_gameObject() { }
	// RVA: 0x68831cc VA: 0x7598e9b1cc
	public Component GetComponent(Type type) { }
	// RVA: 0x6883288 VA: 0x7598e9b288
	internal Void GetComponentFastPath(Type type, IntPtr oneFurtherThanResultValue) { }
	// RVA: 0x VA: 0x0
	public T GetComponent() { }
	// RVA: 0x68832dc VA: 0x7598e9b2dc
	public Boolean TryGetComponent(Type type, out Component component) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetComponent(out T component) { }
	// RVA: 0x68833e4 VA: 0x7598e9b3e4
	public Component GetComponent(String type) { }
	// RVA: 0x6883428 VA: 0x7598e9b428
	public Component GetComponentInChildren(Type t, Boolean includeInactive) { }
	// RVA: 0x6883504 VA: 0x7598e9b504
	public Component GetComponentInChildren(Type t) { }
	// RVA: 0x VA: 0x0
	public T GetComponentInChildren(Boolean includeInactive) { }
	// RVA: 0x VA: 0x0
	public T GetComponentInChildren() { }
	// RVA: 0x688350c VA: 0x7598e9b50c
	public Component[] GetComponentsInChildren(Type t, Boolean includeInactive) { }
	// RVA: 0x6883620 VA: 0x7598e9b620
	public Component[] GetComponentsInChildren(Type t) { }
	// RVA: 0x VA: 0x0
	public T[] GetComponentsInChildren(Boolean includeInactive) { }
	// RVA: 0x VA: 0x0
	public Void GetComponentsInChildren(Boolean includeInactive, List`1 result) { }
	// RVA: 0x VA: 0x0
	public T[] GetComponentsInChildren() { }
	// RVA: 0x VA: 0x0
	public Void GetComponentsInChildren(List`1 results) { }
	// RVA: 0x6883674 VA: 0x7598e9b674
	public Component GetComponentInParent(Type t, Boolean includeInactive) { }
	// RVA: 0x6883750 VA: 0x7598e9b750
	public Component GetComponentInParent(Type t) { }
	// RVA: 0x VA: 0x0
	public T GetComponentInParent(Boolean includeInactive) { }
	// RVA: 0x VA: 0x0
	public T GetComponentInParent() { }
	// RVA: 0x68837cc VA: 0x7598e9b7cc
	public Component[] GetComponentsInParent(Type t, Boolean includeInactive) { }
	// RVA: 0x68838e0 VA: 0x7598e9b8e0
	public Component[] GetComponentsInParent(Type t) { }
	// RVA: 0x VA: 0x0
	public T[] GetComponentsInParent(Boolean includeInactive) { }
	// RVA: 0x VA: 0x0
	public Void GetComponentsInParent(Boolean includeInactive, List`1 results) { }
	// RVA: 0x VA: 0x0
	public T[] GetComponentsInParent() { }
	// RVA: 0x68838e8 VA: 0x7598e9b8e8
	public Component[] GetComponents(Type type) { }
	// RVA: 0x68839e0 VA: 0x7598e9b9e0
	private Void GetComponentsForListInternal(Type searchType, Object resultList) { }
	// RVA: 0x6883a34 VA: 0x7598e9ba34
	public Void GetComponents(Type type, List`1 results) { }
	// RVA: 0x VA: 0x0
	public Void GetComponents(List`1 results) { }
	// RVA: 0x6883a88 VA: 0x7598e9ba88
	public String get_tag() { }
	// RVA: 0x6883b34 VA: 0x7598e9bb34
	public Void set_tag(String value) { }
	// RVA: 0x VA: 0x0
	public T[] GetComponents() { }
	// RVA: 0x6883bf0 VA: 0x7598e9bbf0
	public Boolean CompareTag(String tag) { }
	// RVA: 0x6883cac VA: 0x7598e9bcac
	public Void SendMessageUpwards(String methodName, Object value, SendMessageOptions options) { }
	// RVA: 0x6883d08 VA: 0x7598e9bd08
	public Void SendMessageUpwards(String methodName, Object value) { }
	// RVA: 0x6883d60 VA: 0x7598e9bd60
	public Void SendMessageUpwards(String methodName) { }
	// RVA: 0x6883dac VA: 0x7598e9bdac
	public Void SendMessageUpwards(String methodName, SendMessageOptions options) { }
	// RVA: 0x6883e04 VA: 0x7598e9be04
	public Void SendMessage(String methodName, Object value) { }
	// RVA: 0x6883eb8 VA: 0x7598e9beb8
	public Void SendMessage(String methodName) { }
	// RVA: 0x6883e5c VA: 0x7598e9be5c
	public Void SendMessage(String methodName, Object value, SendMessageOptions options) { }
	// RVA: 0x6883f04 VA: 0x7598e9bf04
	public Void SendMessage(String methodName, SendMessageOptions options) { }
	// RVA: 0x6883f5c VA: 0x7598e9bf5c
	public Void BroadcastMessage(String methodName, Object parameter, SendMessageOptions options) { }
	// RVA: 0x6883fb8 VA: 0x7598e9bfb8
	public Void BroadcastMessage(String methodName, Object parameter) { }
	// RVA: 0x6884010 VA: 0x7598e9c010
	public Void BroadcastMessage(String methodName) { }
	// RVA: 0x688405c VA: 0x7598e9c05c
	public Void BroadcastMessage(String methodName, SendMessageOptions options) { }
	// RVA: 0x68830f4 VA: 0x7598e9b0f4
	public Void .ctor() { }
}
```