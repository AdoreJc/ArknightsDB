# PortConnection

**Namespace:** ` `


## Fields

- `String fieldName`

- `Node node`

- `NodePort port`


## Properties

- `NodePort Port`


## Methods

- `NodePort get_Port()`

- `NodePort GetPort()`


## Dump
```C#
// Dll : XNode.dll
// Namespace : 
private class PortConnection
{
	public String fieldName; // 0x10
	public Node node; // 0x18
	private NodePort port; // 0x20
	public List`1 reroutePoints; // 0x28

	public NodePort Port { get; }

	// RVA: 0x6a91dcc VA: 0x75990a9dcc
	public NodePort get_Port() { }
	// RVA: 0x6a92288 VA: 0x75990aa288
	public Void .ctor(NodePort port) { }
	// RVA: 0x6a92c74 VA: 0x75990aac74
	private NodePort GetPort() { }
}
```