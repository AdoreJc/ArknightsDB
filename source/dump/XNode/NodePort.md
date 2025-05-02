# NodePort

**Namespace:** `XNode`


## Fields

- `Type valueType`

- `String _fieldName`

- `Node _node`

- `String _typeQualifiedName`

- `IO _direction`

- `ConnectionType _connectionType`

- `TypeConstraint _typeConstraint`

- `Boolean _dynamic`


## Properties

- `Int32 ConnectionCount`

- `NodePort Connection`

- `IO direction`

- `ConnectionType connectionType`

- `TypeConstraint typeConstraint`

- `Boolean IsConnected`

- `Boolean IsInput`

- `Boolean IsOutput`

- `String fieldName`

- `Node node`

- `Boolean IsDynamic`

- `Boolean IsStatic`

- `Type ValueType`


## Methods

- `Int32 get_ConnectionCount()`

- `NodePort get_Connection()`

- `IO get_direction()`

- `ConnectionType get_connectionType()`

- `TypeConstraint get_typeConstraint()`

- `Boolean get_IsConnected()`

- `Boolean get_IsInput()`

- `Boolean get_IsOutput()`

- `String get_fieldName()`

- `Node get_node()`

- `Boolean get_IsDynamic()`

- `Boolean get_IsStatic()`

- `Type get_ValueType()`

- `Void set_ValueType(Type)`

- `Void VerifyConnections()`

- `Object GetOutputValue()`

- `Object GetInputValue()`

- `T GetInputValue()`

- `Boolean TryGetInputValue(out)`

- `Single GetInputSum(Single)`

- `Int32 GetInputSum(Int32)`

- `Void Connect(NodePort)`

- `NodePort GetConnection(Int32)`

- `Int32 GetConnectionIndex(NodePort)`

- `Boolean IsConnectedTo(NodePort)`

- `Boolean CanConnectTo(NodePort)`

- `Void Disconnect(NodePort)`

- `Void Disconnect(Int32)`

- `Void ClearConnections()`

- `Void SwapConnections(NodePort)`

- `Void AddConnections(NodePort)`

- `Void MoveConnections(NodePort)`

- `Void Redirect(List`1, List`1)`

- `Boolean <Disconnect>b__59_0(PortConnection)`


## Dump
```C#
// Dll : XNode.dll
// Namespace : XNode
public class NodePort
{
	private Type valueType; // 0x10
	private String _fieldName; // 0x18
	private Node _node; // 0x20
	private String _typeQualifiedName; // 0x28
	private List`1 connections; // 0x30
	private IO _direction; // 0x38
	private ConnectionType _connectionType; // 0x3c
	private TypeConstraint _typeConstraint; // 0x40
	private Boolean _dynamic; // 0x44

	public Int32 ConnectionCount { get; }
	public NodePort Connection { get; }
	public IO direction { get; set; }
	public ConnectionType connectionType { get; set; }
	public TypeConstraint typeConstraint { get; set; }
	public Boolean IsConnected { get; }
	public Boolean IsInput { get; }
	public Boolean IsOutput { get; }
	public String fieldName { get; }
	public Node node { get; }
	public Boolean IsDynamic { get; }
	public Boolean IsStatic { get; }
	public Type ValueType { get; set; }

	// RVA: 0x6a91cd8 VA: 0x75990a9cd8
	public Int32 get_ConnectionCount() { }
	// RVA: 0x6a91d20 VA: 0x75990a9d20
	public NodePort get_Connection() { }
	// RVA: 0x6a91e0c VA: 0x75990a9e0c
	public IO get_direction() { }
	// RVA: 0x6a91e14 VA: 0x75990a9e14
	internal Void set_direction(IO value) { }
	// RVA: 0x6a91e1c VA: 0x75990a9e1c
	public ConnectionType get_connectionType() { }
	// RVA: 0x6a91e24 VA: 0x75990a9e24
	internal Void set_connectionType(ConnectionType value) { }
	// RVA: 0x6a91e2c VA: 0x75990a9e2c
	public TypeConstraint get_typeConstraint() { }
	// RVA: 0x6a91e34 VA: 0x75990a9e34
	internal Void set_typeConstraint(TypeConstraint value) { }
	// RVA: 0x6a91e3c VA: 0x75990a9e3c
	public Boolean get_IsConnected() { }
	// RVA: 0x6a8d91c VA: 0x75990a591c
	public Boolean get_IsInput() { }
	// RVA: 0x6a8d470 VA: 0x75990a5470
	public Boolean get_IsOutput() { }
	// RVA: 0x6a91e8c VA: 0x75990a9e8c
	public String get_fieldName() { }
	// RVA: 0x6a91e94 VA: 0x75990a9e94
	public Node get_node() { }
	// RVA: 0x6a91e9c VA: 0x75990a9e9c
	public Boolean get_IsDynamic() { }
	// RVA: 0x6a8c014 VA: 0x75990a4014
	public Boolean get_IsStatic() { }
	// RVA: 0x6a8ee50 VA: 0x75990a6e50
	public Type get_ValueType() { }
	// RVA: 0x6a8ef38 VA: 0x75990a6f38
	public Void set_ValueType(Type value) { }
	// RVA: 0x6a90534 VA: 0x75990a8534
	public Void .ctor(FieldInfo fieldInfo) { }
	// RVA: 0x6a8f19c VA: 0x75990a719c
	public Void .ctor(NodePort nodePort, Node node) { }
	// RVA: 0x6a8bea4 VA: 0x75990a3ea4
	public Void .ctor(String fieldName, Type type, IO direction, ConnectionType connectionType, TypeConstraint typeConstraint, Node node) { }
	// RVA: 0x6a8bcdc VA: 0x75990a3cdc
	public Void VerifyConnections() { }
	// RVA: 0x6a91ea4 VA: 0x75990a9ea4
	public Object GetOutputValue() { }
	// RVA: 0x6a91edc VA: 0x75990a9edc
	public Object GetInputValue() { }
	// RVA: 0x6a91ef8 VA: 0x75990a9ef8
	public Object[] GetInputValues() { }
	// RVA: 0x VA: 0x0
	public T GetInputValue() { }
	// RVA: 0x VA: 0x0
	public T[] GetInputValues() { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetInputValue(out T value) { }
	// RVA: 0x6a92048 VA: 0x75990aa048
	public Single GetInputSum(Single fallback) { }
	// RVA: 0x6a92118 VA: 0x75990aa118
	public Int32 GetInputSum(Int32 fallback) { }
	// RVA: 0x6a8f588 VA: 0x75990a7588
	public Void Connect(NodePort port) { }
	// RVA: 0x6a8ed24 VA: 0x75990a6d24
	public List`1 GetConnections() { }
	// RVA: 0x6a92350 VA: 0x75990aa350
	public NodePort GetConnection(Int32 i) { }
	// RVA: 0x6a92498 VA: 0x75990aa498
	public Int32 GetConnectionIndex(NodePort port) { }
	// RVA: 0x6a921e0 VA: 0x75990aa1e0
	public Boolean IsConnectedTo(NodePort port) { }
	// RVA: 0x6a8f27c VA: 0x75990a727c
	public Boolean CanConnectTo(NodePort port) { }
	// RVA: 0x6a9253c VA: 0x75990aa53c
	public Void Disconnect(NodePort port) { }
	// RVA: 0x6a9268c VA: 0x75990aa68c
	public Void Disconnect(Int32 i) { }
	// RVA: 0x6a8c024 VA: 0x75990a4024
	public Void ClearConnections() { }
	// RVA: 0x6a927dc VA: 0x75990aa7dc
	public List`1 GetReroutePoints(Int32 index) { }
	// RVA: 0x6a92840 VA: 0x75990aa840
	public Void SwapConnections(NodePort targetPort) { }
	// RVA: 0x6a92afc VA: 0x75990aaafc
	public Void AddConnections(NodePort targetPort) { }
	// RVA: 0x6a92b9c VA: 0x75990aab9c
	public Void MoveConnections(NodePort targetPort) { }
	// RVA: 0x6a91864 VA: 0x75990a9864
	public Void Redirect(List`1 oldNodes, List`1 newNodes) { }
	// RVA: 0x6a92c4c VA: 0x75990aac4c
	private Boolean <Disconnect>b__59_0(PortConnection it) { }
}
```