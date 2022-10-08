# DEMO

some plain text


## Subheader


New plain text

## Local Development

1. open index.html in your browser.

2. added from quick-test branch

3. this one added local main branch

<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>HTML and CSS for Complete Beginners: Example 3-8-2</title>

    <!-- This CSS and font is purely for presentational purposes. -->
    <link rel="stylesheet" href="css/presentation.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;900&display=swap"
      rel="stylesheet"
    />

    <style>
      * {
        box-sizing: border-box;
      }

      .wrapper {
        /* Don't worry about what flex or gap means. */
        /* It's simply here for demo purposes. */
        display: flex;
        gap: 2rem;
      }

      .widget {
        width: 100%;
        min-width: 250px;
        max-width: 300px;
        background-color: #f3f4f5;
        /* padding-top: 2rem;
        padding-right: 2rem;
        padding-bottom: 2rem;
        padding-left: 2rem; */
        padding: 2rem;
        /* padding: 1rem 2rem 3rem 4rem; */
      }

      .widget img {
        width: 4rem;
      }

      .main-icon {
        /* The display property is used for demo purposes. */
        display: block;
        margin-bottom: 2rem;
      }

      .widget button {
        padding: 8px 24px;
      }

      .widget p img {
        width: 1.25rem;
        margin-right: 8px;
      }

      .widget button img {
        height: 1rem;
      }

      .widget h2,
      .widget p {
        margin: 0;
      }

      .widget h2 {
        margin: 0.5rem 0;
      }

      .widget p {
        margin-bottom: 2rem;
      }
    </style>
  </head>
  <body class="flip">
    <section class="learn">
      <!-- Practice area start -->

      <h1>Dashboard</h1>

      <div class="wrapper">
        <div class="widget">
          <img
            src="images/example/icon-money.svg"
            class="main-icon"
            alt="Icon"
          />
          <h2>$4,502</h2>
          <p>Earned this month</p>
          <p>
            <img
              src="images/example/icon-arrow-green.svg"
              alt="Arrow green"
            />+6.05% <span>than last month</span>
          </p>
          <button>
            Earnings
            <img src="images/example/icon-arrow-right.svg" alt="Arrow right" />
          </button>
        </div>
        <div class="widget">
          <img
            src="images/example/icon-sales.svg"
            class="main-icon"
            alt="Icon"
          />
          <h2>22</h2>
          <p>New Sales</p>
          <p>
            <img
              src="images/example/icon-arrow-green.svg"
              alt="Arrow green"
            />+16.64% <span>than last month</span>
          </p>
          <button>
            Sales
            <img src="images/example/icon-arrow-right.svg" alt="Arrow right" />
          </button>
        </div>
        <div class="widget">
          <img
            src="images/example/icon-chat.svg"
            class="main-icon"
            alt="Icon"
          />
          <h2>7</h2>
          <p>New comments</p>
          <p>
            <img src="images/example/icon-arrow-red.svg" alt="Arrow red" /> -19%
            <span>than last month</span>
          </p>
          <button>
            Comments
            <img src="images/example/icon-arrow-right.svg" alt="Arrow right" />
          </button>
        </div>
      </div>

      <!-- Practice area end -->
    </section>

    <section class="preview" data-content="lesson 3-8: The CSS Box Model">
      <img
        width="971px"
        src="images/reference/dashboard.png"
        alt="Reference image"
      />
    </section>
  </body>
</html>
