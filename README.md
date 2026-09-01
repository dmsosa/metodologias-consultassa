# Custom Website, UF1305

Objective:
With the knowledge acquired, create a Web page, implementing the resources provided; html, css, js, semantic tags, grid, DOM, professionally adding relational documentation of the certificate studied, IFCD0110.

The goal with this project is to mimic an ecommerce from scratch for educational purposes, trying to grasp web development concepts for a strong foundation in web development.

# The shopping form:

I grab all the items from my backend database, during development, I import it rather from a local data.ts package, how can this be done?

## The items

how to gra

Create a form, documentation, download options, links to resources and implement simulated contact possibilities as if you were a company.

Encourage and give creative but professional imagination.

# What is my page about?

This website is going to be about Sport suplements and Fitness merchandising. I have a form with following entries:

```
<form>
username
email
password
confirm password
disability
agrees gdpr
age
birthday

contact form
textarea
email
subject
</form>

<home>
grid showing different products image, you can download a description for them

links to different resources like wikipedia pages
</home>

```

Need to implement:

Grid with product cards and how to download them.
Each product is a class TProduct, which has a title, description, image, stock and price
How to change between pages? easy, react pages.

# Routes

I need to do the following routes:
- Home, this shows a grid with items that are retrieved from the backend, for development I will import items from the local data.ts folder. After the grid we have a pagination and a small paragraph with image.

- Items displays a bigger grid of size 6 with pagination, the header of my page has a button which allows the user to go to the shopping routes. 

Since my form builds dynamically on the go from different routes, what is the better approach? I think about creating a route checkout which has an Outlet for other child routes.
- (checkout/core) asks for username, email, and number
- (checkout/address) asks for delivery and invoice address
- (checkout/payment) asks for payment methods
- (checkout/items) shows all items currently selected, and allow you to add extra items.

### BONUS

How to autofill username, email and number, and address based on the user that is currently logged In?

- Contact, static content, 3 sections, paragraph and images.

- Form 



# My page Caracteristics

I need to do a form, which controls the following information:

username
email
address
mobile
country
orderedItems

TODO:

Grid showing items.
Item preview component.

Bonus:
Add item properties like a Record<string, string>
Make item image zoomable and add discount price field
add tags to articles

