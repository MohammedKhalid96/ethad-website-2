<template>
  <div class="contact-form">
    <form action="#" method="post">
      <div class="row">
        <div class="col-6">
          <div class="form-group">
            <input
              type="text"
              class="form-control"
              name="name"
              id="form-name"
              aria-describedby="name"
              placeholder="برجاء ادخال الأسم"
              required
            />
          </div>
        </div>

        <div class="col-6">
          <div class="form-group">
            <input
              type="tel"
              class="form-control"
              name="phone"
              id="form-phone"
              aria-describedby="phone"
              placeholder="برجاء ادخال رقم الهاتف"
              required
            />
          </div>
        </div>
      </div>

      <div class="form-group">
        <input
          type="email"
          class="form-control"
          name="email"
          id="form-email"
          aria-describedby="email"
          placeholder="برجاء ادخال البريد الالكتروني"
          required
        />
      </div>

      <div class="form-group">
        <textarea
          type="text"
          class="form-control msg-box"
          rows="5"
          name="msg"
          id="form-msg"
          aria-describedby="msg"
          placeholder="الرسالة"
        ></textarea>
      </div>

      <div class="form-group action-btn-wrap">
        <button type="submit" class="btn action-btn link">
          <span class="link-arrow">
            <font-awesome-icon icon="paper-plane"></font-awesome-icon>
          </span>
          أرسال
        </button>
      </div>
    </form>
  </div>
</template>
