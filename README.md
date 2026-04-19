<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skyline Properties || Real Estate Listings</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<nav class="navbar navbar-dark bg-dark mb-4">
    <div class="container">
        <a class="navbar-brand fw-bold" href="#">🏙️ Skyline Properties</a>
    </div>
</nav>

<div class="container">
    <div class="row">
        <aside class="col-lg-3 mb-4">
            <div class="sidebar border shadow-sm">
                <h5 class="mb-3">Filter Properties</h5>
                
                <div class="mb-3">
                    <label class="form-label">Price Range</label>
                    <select class="form-select">
                        <option selected>All Prices</option>
                        <option>100k - 300k</option>
                        <option>300k - 600k</option>
                        <option>600k+</option>
                    </select>
                </div>

                <div class="mb-3">
                    <label class="form-label">BHK (Bedrooms)</label>
                    <select class="form-select">
                        <option selected>Any</option>
                        <option>1 BHK</option>
                        <option>2 BHK</option>
                        <option>3 BHK</option>
                        <option>4+ BHK</option>
                    </select>
                </div>

                <button class="btn btn-primary w-100">Apply Filters</button>
            </div>
        </aside>

        <main class="col-lg-9">
            <div class="row row-cols-1 row-cols-md-2 row-cols-xl-3 g-4">
                
                <div class="col">
                    <div class="card h-100 property-card border-0 shadow-sm" data-bs-toggle="modal" data-bs-target="#propertyModal">
                        <img src="https://images.unsplash.com/photo-1568605114967-8130f3a36994?auto=format&fit=crop&w=500&q=80" class="card-img-top" alt="Modern Villa">
                        <div class="card-body">
                            <h5 class="card-title text-primary">$450,000</h5>
                            <p class="card-text mb-1"><strong>3 BHK Luxury Villa</strong></p>
                            <p class="text-muted small">Sunset , GOA</p>
                            <span class="badge bg-success">For Sale</span>
                        </div>
                    </div>
                </div>

                <div class="col">
                    <div class="card h-100 property-card border-0 shadow-sm" data-bs-toggle="modal" data-bs-target="#propertyModal">
                        <img src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=500&q=80" class="card-img-top" alt="Penthouse">
                        <div class="card-body">
                            <h5 class="card-title text-primary">820,000</h5>
                            <p class="card-text mb-1"><strong>4 BHK Penthouse</strong></p>
                            <p class="text-muted small">Skyline Heights, Manhattan</p>
                            <span class="badge bg-warning text-dark">Premium</span>
                        </div>
                    </div>
                </div>

                <div class="col">
                    <div class="card h-100 property-card border-0 shadow-sm" data-bs-toggle="modal" data-bs-target="#propertyModal">
                        <img src="https://images.unsplash.com/photo-1570129477492-45c003edd2be?auto=format&fit=crop&w=500&q=80" class="card-img-top" alt="Family Home">
                        <div class="card-body">
                            <h5 class="card-title text-primary">$275,000</h5>
                            <p class="card-text mb-1"><strong>2 BHK Suburban Home</strong></p>
                            <p class="text-muted small">Oakwood Dr, New Jersey</p>
                            <span class="badge bg-info text-dark">Reduced</span>
                        </div>
                    </div>
                </div>

            </div>
        </main>
    </div>
</div>

<div class="modal fade" id="propertyModal" tabindex="-1" aria-labelledby="modalTitle" aria-hidden="true">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="modalTitle">Property Details</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
                <div class="row">
                    <div class="col-md-6">
                        <img src="https://images.unsplash.com/photo-1568605114967-8130f3a36994?auto=format&fit=crop&w=800&q=80" class="img-fluid rounded mb-3" alt="Full view">
                    </div>
                    <div class="col-md-6">
                        <h3>Skyline Luxury Estate</h3>
                        <p class="text-primary h4 mb-3">$450,000</p>
                        <ul class="list-group list-group-flush mb-3">
                            <li class="list-group-item"> 3 Bedrooms (BHK)</li>
                            <li class="list-group-item"> 2 Bathrooms</li>
                            <li class="list-group-item"> 2,400 Sq Ft</li>
                            <li class="list-group-item"> 2 Parking Spaces</li>
                        </ul>
                        <p>This stunning property features modern architecture, high-end finishes, and a spacious backyard perfect for entertaining.</p>
                    </div>
                </div>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                <button type="button" class="btn btn-primary">Contact Agent</button>
            </div>
        </div>
    </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</body>
</html>
