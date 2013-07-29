# compute
--
    import "github.com/gcloud/compute"

GCloud compute package for cloud services.

## Usage

#### type Images

```go
type Images struct {
	identity.Account
}
```

The images available from the compute service.

#### func (*Images) Destroy

```go
func (s *Images) Destroy()
```
Destroy a image.

#### func (*Images) Distribute

```go
func (s *Images) Distribute()
```
Distribute images to mutliple regions.

#### func (*Images) List

```go
func (s *Images) List()
```
List images available to the account.

#### func (*Images) Show

```go
func (s *Images) Show(id string)
```
Show image information for a given id.

#### type Locations

```go
type Locations struct{}
```

The locations provided by a compute service.

#### func (*Locations) List

```go
func (s *Locations) List()
```
List available locations.

#### func (*Locations) Show

```go
func (s *Locations) Show(id string)
```
Show location information for a given id.

#### type Servers

```go
type Servers struct {
	identity.Account
}
```

The Servers type interacts with Compute services.

#### func (*Servers) Create

```go
func (s *Servers) Create()
```
Create a server.

#### func (*Servers) Destroy

```go
func (s *Servers) Destroy()
```
Destroy a server.

#### func (*Servers) List

```go
func (s *Servers) List()
```
List servers available on the account.

#### func (*Servers) Reboot

```go
func (s *Servers) Reboot()
```
Reboot a server.

#### func (*Servers) Show

```go
func (s *Servers) Show(id string)
```
Show server information for a given id.

#### func (*Servers) Start

```go
func (s *Servers) Start()
```
Start a server that is stopped.

#### func (*Servers) Stop

```go
func (s *Servers) Stop()
```
Stop a server that is running.

#### type Sizes

```go
type Sizes struct{}
```

The sizes offered by the compute service.

#### func (*Sizes) List

```go
func (s *Sizes) List()
```
List available sizes.

#### func (*Sizes) Show

```go
func (s *Sizes) Show(id string)
```
Show size information for a given id.
