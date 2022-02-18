describe('select element', () => {

    beforeEach(() => {

        cy.visit('https://insurance.lotussmoney.com/')

    })

    it('Test1', () => {
        cy.get('.v-tab').then( item => item[0].click())
        cy.wait(2000)
        cy.get('.v-btn__content').then( item => item[3].click())
        cy.wait(2000)
        cy.get('.modal__cartype__button--container').then( item => item[5].click())
        cy.wait(2000)
        cy.get('.button__togglegroup--default').then( item => item[17].click())
        cy.wait(2000)
        cy.get('.desktop__dialog__vcard .v-card__text').scrollTo('bottom')
        cy.wait(2000)
        cy.get('.modal__carmodel__content').then( item => item[49].click())
        cy.wait(2000)
        cy.get('.modal__carsubmodel__content').then( item => item[1].click())
        cy.wait(2000)
        cy.get('.modal__caryear__content').then( item => item[9].click())
        cy.wait(2000)
        cy.get('.button__togglegroup--default').then( item => item[92].click())
        cy.wait(2000)
        cy.get('.v-input--selection-controls__ripple').then( item => item[3].click())
        cy.wait(2000)
        cy.get('[id="producttype__submit--custom"]').click();
        cy.wait(2000)
       
    });


});
