# storage
--
    import "github.com/gcloud/storage"

This package provides object storage services for GCloud, the cloud abstraction
layer in GO.

## Usage

#### type Containers

```go
type Containers struct {
	identity.Account
}
```

The containers available from the storage service.

#### func (*Containers) Create

```go
func (s *Containers) Create()
```
Create a container.

#### func (*Containers) Destroy

```go
func (s *Containers) Destroy()
```
Destroy a container.

#### func (*Containers) Distribute

```go
func (s *Containers) Distribute()
```
Distribute containers to mutliple regions.

#### func (*Containers) List

```go
func (s *Containers) List()
```
List containers available to the account.

#### func (*Containers) Show

```go
func (s *Containers) Show(id string)
```
Show container information for a given id.

#### type Objects

```go
type Objects struct {
	identity.Account
	Containers
}
```

The objects available from the storage service.

#### func (*Objects) Create

```go
func (s *Objects) Create()
```
Create an object.

#### func (*Objects) Destroy

```go
func (s *Objects) Destroy()
```
Destroy an object.

#### func (*Objects) List

```go
func (s *Objects) List()
```
List objects available to the account.

#### func (*Objects) Show

```go
func (s *Objects) Show(id string)
```
Show object information for a given id.
