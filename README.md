    <h1 class="display-4 fw-bold text-light">Makoto Productions</h1>
        <div class="col-lg-6 mx-auto">
            <p class="lead mb-4 text-light">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates totam sunt at numquam iusto mollitia. Veritatis reiciendis architecto voluptatem, nihil eligendi corporis neque possimus modi amet? Mollitia similique numquam ipsum!</p>
            <p class="lead mb-4 text-light">Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia sit deleniti eaque dignissimos sequi minima minus temporibus magni pariatur expedita quidem mollitia, tempora possimus quos quas, eligendi provident dolores officiis.</p>
        </div>
    </div>
    <div class="row row-cols-1 row-cols-md-3 g-4 px-4 mt-5 mb-5">
        <div class="col">
          <div class="card">
            <img src="https://picsum.photos/1024/500" class="img-fluid rounded-3 shadow-lg d-block w-100"
                        alt="Example image" width="1024" height="500" loading="lazy">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <img src="https://picsum.photos/1024/501" class="img-fluid rounded-3 shadow-lg d-block w-100"
                        alt="Example image" width="1024" height="500" loading="lazy">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <img src="https://picsum.photos/1024/502" class="img-fluid rounded-3 shadow-lg d-block w-100"
                        alt="Example image" width="1024" height="500" loading="lazy">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content.</p>
            </div>
          </div>
        </div>
      </div>
    <div class="container">
        <h2 class="display-4 fw-bold text-light text-center">Coments</h2>
        <form class="row g-3">
            <div class="col-md-6">
              <label for="validationDefault01" class="form-label text-light">First name</label>
              <input type="text" class="form-control bg-secondary text-light" id="validationDefault01" value="Mark" required>
            </div>
            <div class="col-md-6">
              <label for="validationDefault02" class="form-label text-light">Last name</label>
              <input type="text" class="form-control bg-secondary text-light" id="validationDefault02" value="Otto" required>
            </div>
            <div class="col-md-7">
              <label for="validationDefault03" class="form-label text-light">Country</label>
              <input type="text" class="form-control bg-secondary text-light" id="validationDefault03" required>
            </div>
            <div class="col-md-5">
              <label for="validationDefault04" class="form-label text-light">City</label>
              <select class="form-select bg-secondary text-light" id="validationDefault04" required>
                <option selected disabled value="">Choose...</option>
                <option>...</option>
              </select>
            </div>
            <div class="col-md-12">
              <label for="validationDefault04" class="form-label text-light">Coment</label>
              <div class="form-floating">
                <textarea class="form-control bg-secondary text-light" id="floatingTextarea2" style="height: 200px"></textarea>
              </div>
            </div>
            <div class="col-12">
              <div class="form-check">
                <input class="form-check-input" type="checkbox" value="" id="invalidCheck2" required>
                <label class="form-check-label text-light" for="invalidCheck2">
                  Agree to terms and conditions
                </label>
              </div>
            </div>
            <div class="col-12 text-center mb-5">
              <button class="btn btn-success" type="submit">Submit form</button>
            </div>
          </form>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
